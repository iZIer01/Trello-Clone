# Trello Clone  

## Intro  
I built this app to practice **DOM Manipulation**, **Drag & Drop**, and **localStorage**.  
The idea is a **Kanban board** like Trello, where tasks move between columns.  

---

## Level 1 – Setup Columns  

### Case Study  
Every Trello board has at least 3 columns.  

### Goal  
- Create HTML structure with 3 columns.  
- Add CSS to make them side by side.  

### Steps  
- Add `<div>` for **To Do**, **In Progress**, **Done**.  
- Style with flexbox.  
- Give each column a title.  

---

## Level 2 – Add Tasks  

### Case Study  
Tasks must be created by the user.  

### Goal  
- Input + button for adding tasks.  
- Append task cards to “To Do” column.  

### Steps  
- Create form with input.  
- Add event listener on button.  
- When clicked, create a new `<div class=\"card\">`.  

---

## Level 3 – Drag and Drop  

### Case Study  
Tasks move across columns in real life, so our app must allow that.  

### Goal  
- Drag task cards.  
- Drop them into other columns.  

### Steps  
- Add `draggable=\"true\"` to task.  
- Listen for `dragstart`, `dragover`, `drop` events.  
- Update DOM accordingly.  

---

## Level 4 – LocalStorage  

### Case Study  
Tasks should stay after refresh.  

### Goal  
- Save board state in localStorage.  
- Load it back on page load.  

### Steps  
- Convert board data to JSON.  
- Use `localStorage.setItem()` to save.  
- Use `localStorage.getItem()` to load.  

---

## Level 5 – Extra Features  

### Case Study  
To stand out to recruiters, the app must have extras.  

### Goal  
- Dark/Light mode toggle.  
- Due dates + urgency colors.  
- Export tasks as JSON file.  

### Steps  
- Add toggle button, switch CSS class.  
- Add date picker when creating tasks.  
- Compare current date with due date.  
- Add export button → `JSON.stringify()` data.  

---

## Visual Design  
- Header with app title.  
- 3 columns side by side.  
- Each card has title + due date.  
- Toggle for Dark/Light mode.  

---
