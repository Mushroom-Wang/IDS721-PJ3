# MongoDB with Rust
Demonstrates how to connect to a MongoDB database and perform CRUD (create, read, update, delete) operations using the MongoDB Rust driver.

## Usage
The Rust-MongoDB-Project provides the following functionalities:

- `create` - creates a new document in the database.
- `read` - reads a document from the database.
- `update` - updates an existing document in the database.
- `delete` - deletes a document from the database.

## Example
Create a new document
```
./target/release/rust-mongodb-project create --name "John Doe" --email "johndoe@example.com"
```
Read a document
```
./target/release/rust-mongodb-project read --id 1234567890
```
Update a document
```
./target/release/rust-mongodb-project update --id 1234567890 --name "Jane Doe" --email "janedoe@example.com"
```
Delete a document
```
./target/release/rust-mongodb-project update --id 1234567890 --name "Jane Doe" --email "janedoe@example.com"
```

## References

* [rust-cli-template](https://github.com/kbknapp/rust-cli-template)
