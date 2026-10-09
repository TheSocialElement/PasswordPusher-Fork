release: bundle exec rails db:prepare
web: HTTP_PORT=$PORT TARGET_PORT=5100 PORT=5100 bundle exec bin/thrust bin/rails server
worker: bundle exec rake solid_queue:start
