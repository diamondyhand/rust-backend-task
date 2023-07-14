## Install postgresql and create database (credential is in env file)

Then in a root of the project, run following commands in order.

### `setx LIB "%LIB%;C:\Program Files\PostgreSQL\15\bin"`

### `add system environment variable  C:\Program Files\PostgreSQL\15\lib\`

### `cargo install diesel_cli --no-default-features --features postgres`

### `diesel setup`

### `diesel migration run`

### `cargo run`