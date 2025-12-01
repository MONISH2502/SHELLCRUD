# MongoDB Shell CRUD Interactive Showcase

An interactive web-based reference guide for MongoDB CRUD operations. Learn and practice MongoDB shell commands with instant visual feedback.

## Features

- **Complete CRUD Coverage**: Insert, Read, Update, and Delete operations
- **Interactive Examples**: Click "Run" to see simulated command outputs
- **One-Click Copy**: Copy any MongoDB command to clipboard instantly
- **Visual Feedback**: Hover effects and animations for better UX
- **No Setup Required**: Pure HTML/CSS/JavaScript - runs in any browser

## Operations Covered

### Create
- `insertOne()` - Insert a single document
- `insertMany()` - Insert multiple documents at once

### Read
- `find()` - Query all documents
- `find({filter})` - Query with specific criteria

### Update
- `updateOne()` - Update a single document
- `updateMany()` - Update multiple documents matching criteria

### Delete
- `deleteOne()` - Remove a single document
- `deleteMany()` - Remove multiple documents matching criteria

## Quick Start

1. Open `index.html` in any modern browser
2. Browse the MongoDB commands organized by CRUD operation
3. Click "Copy" to copy any command to clipboard
4. Click "Run" to see simulated output
5. Use these commands in your actual MongoDB shell

## Use Cases

- **Learning MongoDB**: Perfect for beginners learning CRUD operations
- **Quick Reference**: Keep it open while working with MongoDB
- **Teaching Tool**: Use in classrooms or workshops
- **Command Templates**: Copy-paste ready commands for common operations

## Example Commands

```javascript
// Insert a student
db.students.insertOne({ name: "Asha", age: 21, dept: "MCA" })

// Find all MCA students
db.students.find({ dept: "MCA" }).pretty()

// Update student age
db.students.updateOne({ name: "Naveen" }, { $set: { age: 22 } })

// Delete a student
db.students.deleteOne({ name: "Charan" })
```

## Technologies

Pure HTML, CSS, and JavaScript with no external dependencies.

## License

MIT License

---

**Note**: This is a demonstration tool with simulated outputs. Run these commands in an actual MongoDB shell or MongoDB Compass for real database operations.
