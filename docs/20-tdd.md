# 20. Technical Design Document Summary

The platform uses simple HTTP verb mappings to handle data operations. The client sends clean requests (`GET` to read assets, `POST` to handle entries, `PUT/DELETE` to adjust logs). This keeps the client presentation layer completely separate from the database computational layer.
