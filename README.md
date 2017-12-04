# README

This is a test application to test the issue [Use :bigint for SQLite on references](https://github.com/rails/rails/issues/31329) on Ruby on Rails.

See `db/schema.rb` to see how SQLite uses `:bigint` on table `active_storage_blobs` while it uses `:integer` for references at `post_id` on table `comments`
