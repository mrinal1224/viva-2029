🧩 Problem: Simple Notes App
🎯 Objective

Create a Simple Notes App where users can:

Add notes

Delete individual notes

See total number of notes

🧱 Starter HTML (DO NOT CHANGE)
<input type="text" id="noteInput" placeholder="Enter a note" />
<button id="addNoteBtn">Add Note</button>

<p>Total Notes: <span id="noteCount">0</span></p>

<ul id="noteList"></ul>

📌 Requirements
1️⃣ Add Note

When Add Note is clicked:

Read the value from the input

Ignore empty input

Create a <li> element containing:

The note text

A Delete button

Append the <li> to #noteList

Clear the input field

Update the total note count

2️⃣ Delete Note

When Delete is clicked:

Remove only that note from the list

Update the total note count

🛠️ Rules / Constraints

You must:

Use document.querySelector / getElementById

Use createElement

Use appendChild

Use addEventListener

Not use innerHTML

Not use any framework or library

🧠 Hints (Optional for Students)

Use parentElement.remove() to delete a note

Use children.length to calculate total notes

🧪 Example Flow

Type: Buy milk

Click Add Note

Note appears in list

Total Notes → 1

Add another note

Total Notes → 2

Delete first note

Total Notes → 1
