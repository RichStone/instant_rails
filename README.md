# Instant Rails App Template

## Prerequisites

In order to use Instant Rails, you must have Docker installed.

## Usage instructions

First, clone the repo.

```bash
git clone https://github.com/jasonswett/instant_rails.git
cd instant_rails
```

Then run the `init.sh` script.

```bash
./init.sh your_app_name
```

This script will create a Rails application and start a Rails server.

Once the script finishes, you can visit `localhost:3000` and see your app running.
Check `docker ps` for the exact port (In my case it was 3001).

## Test

```shell
docker exec -it 8a7846e73ff0 bundle exec rspec
```

## Acknowledgements

Forked from https://github.com/jasonswett/instant_rails
