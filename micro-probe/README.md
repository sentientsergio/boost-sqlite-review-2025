# Micro-Probe (Optional)

Option A does not require code. If you choose to validate ergonomics quickly, consider these minimal checks:

1. Open DB → create table → prepared inserts with named & positional binds.  
2. Typed query result into a struct/tuple; intentionally mismatch a column type to observe diagnostics.  
3. Register a simple scalar UDF and call it from SQL.  
4. (Stretch) Sketch an eponymous-only virtual table module; compile and load.

If you add code here, it is licensed under MIT (see `LICENSE-CODE`). Keep it tiny and self-contained.
