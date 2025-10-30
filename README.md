


Step 1: Open a text editor

Open Notepad (or any text editor) on your computer.



 Step 2: Start a new file

Click File → New to create a new blank document.



 Step 3: Type the HTML code below

<!DOCTYPE html>
<html>
<body>

<h2>Job Application Tracker</h2>

<form id="jobForm">
  Company: <input id="company"><br><br>
  Job Title: <input id="title"><br><br>
  Status:
  <select id="status">
    <option>Applied</option>
    <option>Interview</option>
    <option>Offer</option>
    <option>Rejected</option>
  </select><br><br>
  <button>Add</button>
</form>

<table border="1" id="jobTable">
  <tr><th>Company</th><th>Title</th><th>Status</th></tr>
</table>

<script>
  document.getElementById("jobForm").onsubmit = function(e) {
    e.preventDefault();
    let table = document.getElementById("jobTable");
    let row = table.insertRow();
    row.insertCell(0).innerText = company.value;
    row.insertCell(1).innerText = title.value;
    row.insertCell(2).innerText = status.value;
    this.reset();
  }
</script>

</body>
</html>


 Step 4: Save the file

Click File → Save As.
Save it as job_tracker.html.



 Step 5: Choose file type

In the “Save as type” box, select All Files and save with .html extension.


 Step 6: Open the file

Go to the folder where you saved it and double-click job_tracker.html.



 Step 7: View it in browser

It will open in your web browser (like Chrome, Edge, or Firefox).


Step 8: Enter your job details

Type:

Company name

Job title

Select status
Then click Add.



 Step 9: Check your table

Your entered job will appear in the table below instantly.


 Step 10: Add more entries

You can add as many job applications as you want — all will show in the table.


