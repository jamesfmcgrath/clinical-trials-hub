# Clinical Trials Hub

A decoupled Drupal 11 application for managing clinical trial information.

## Tech Stack

- **Backend**: Drupal 11
- **Frontend**: React/Next.js (coming soon)
- **API**: JSON:API
- **Local Dev**: DDEV
- **CI/CD**: GitHub Actions (coming soon)

## Local Development

### Prerequisites

- [DDEV](https://ddev.readthedocs.io/en/stable/)
- Docker Desktop
- Git

### Setup

```bash
git clone [your-repo-url]
cd clinical-trials-hub
ddev start
ddev composer install

# First-time setup
ddev drush site:install standard \
  --account-name=admin \
  --account-pass=admin

# Access the site
ddev launch
```

### Useful Commands

```bash
ddev drush cr          # Clear cache
ddev drush uli         # Get one-time login link
ddev composer require  # Install packages
ddev ssh               # SSH into container
```

## Project Goals

This project demonstrates:

- Drupal 11 custom module development
- JSON:API decoupled architecture
- Modern PHP OOP practices
- CI/CD with GitHub Actions
- Docker containerization
