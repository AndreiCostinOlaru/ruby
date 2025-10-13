# Weblog

A simple blog application built with Rails 8.

## Requirements

- Ruby 3.4.4
- SQLite3
- Node.js (for asset pipeline)

## Setup

```bash
# Install dependencies
bundle install

# Setup database
bin/rails db:prepare

# Start server
bin/rails server
```

Visit http://localhost:3000

## Features

- Create and view blog posts
- Rails 8 with Hotwire
- SQLite database

## Testing

```bash
bin/rails test
bin/rails test:system
```

## Deployment

Configured for deployment with Kamal:

```bash
bin/kamal deploy
```

## Code Quality

- RuboCop for linting: `bin/rubocop`
- Brakeman for security: `bin/brakeman`
