<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Employee Information Form</title>
  <link rel="stylesheet" href="css/bootstrap.min.css">
</head>
<body>
  <div class="container mt-5">
    <h1 class="text-center">EMPLOYEE INFORMATION FORM</h1>
    <hr>

    <form id="employeeForm">
      <h3 class="mt-4">Personal Information</h3>
      <div class="mb-3">
        Full Name: <input type="text" class="form-control" name="fullName" required>
      </div>
      <div class="mb-3">
        Address: <input type="text" class="form-control" name="address" required>
      </div>
      <div class="mb-3">
        Phone Number: <input type="text" class="form-control" name="phone" required>
      </div>
      <div class="mb-3">
        Email: <input type="email" class="form-control" name="email" required>
      </div>

      <h3 class="mt-4">Employment Information</h3>
      <div class="mb-3">
        Title: <input type="text" class="form-control" name="title" required>
      </div>
      <div class="mb-3">
        Department: <input type="text" class="form-control" name="department" required>
      </div>
      <div class="mb-3">
        Date of Hire: <input type="date" class="form-control" name="hireDate" required>
      </div>
      <div class="mb-3">
        Employment Status:<br>
        <div class="form-check form-check-inline">
          <input class="form-check-input" type="checkbox" name="status" value="Full Time">
          <label class="form-check-label">Full Time</label>
        </div>
        <div class="form-check form-check-inline">
          <input class="form-check-input" type="checkbox" name="status" value="Part Time">
          <label class="form-check-label">Part Time</label>
        </div>
        <div class="form-check form-check-inline">
          <input class="form-check-input" type="checkbox" name="status" value="Contractor">
          <label class="form-check-label">Contractor</label>
        </div>
        <div class="form-check form-check-inline">
          <input class="form-check-input" type="checkbox" name="status" value="Intern">
          <label class="form-check-label">Intern</label>
        </div>
        <div class="form-check form-check-inline">
          <input class="form-check-input" type="checkbox" name="status" value="Other">
          <label class="form-check-label">Other:</label>
          <input type="text" class="form-control form-control-sm d-inline-block w-auto" name="otherStatus">
        </div>
      </div>

      <h3 class="mt-4">Education</h3>
      <div class="mb-3">
        Highest Level of Education: <input type="text" class="form-control" name="educationLevel" required>
      </div>
      <div class="mb-3">
        Name of Institution: <input type="text" class="form-control" name="institution" required>
      </div>
      <div class="mb-3">
        Degree Earned: <input type="text" class="form-control" name="degree" required>
      </div>
      <div class="mb-3">
        Major/Field of Study: <input type="text" class="form-control" name="major" required>
      </div>
      <div class="mb-3">
        Graduation Date: <input type="date" class="form-control" name="gradDate" required>
      </div>

      <h3 class="mt-4">Professional Experience</h3>
      <div class="mb-3">
        Licenses: <input type="text" class="form-control" name="licenses">
      </div>
      <div class="mb-3">
        Previous Work Experience:
        <textarea class="form-control" name="experience" style="height: 150px;"></textarea>
      </div>

      <h3 class="mt-4">Emergency Contact Information</h3>
      <div class="mb-3">
        Full Name: <input type="text" class="form-control" name="emergencyName" required>
      </div>
      <div class="mb-3">
        Address: <input type="text" class="form-control" name="emergencyAddress" required>
      </div>
      <div class="mb-3">
        Phone Number: <input type="text" class="form-control" name="emergencyPhone" required>
      </div>
      <div class="mb-3">
        Cell Phone Number: <input type="text" class="form-control" name="emergencyCell" required>
      </div>
      <div class="mb-3">
        Relationship: <input type="text" class="form-control" name="relationship" required>
      </div>

      <h3 class="mt-4">Employee Signature</h3>
      <div class="mb-3">
        Signature: <input type="text" class="form-control" name="signature">
      </div>
      <div class="mb-3">
        Date: <input type="text" class="form-control" name="date">
      </div>

      <input type="submit" class="btn btn-primary" value="Submit">
    </form>
  </div>

  <script src="js/bootstrap.bundle.min.js"></script>
  <script src="form.js"></script>
</body>
</html>>

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Employee Information Form</title>
  <link rel="stylesheet" href="css/bootstrap.min.css">
</head>
<body>
  <div class="container mt-5">
    <h1 class="text-center">EMPLOYEE INFORMATION FORM</h1>
    <hr>

    <form id="employeeForm">
      <h3 class="mt-4">Personal Information</h3>
      <div class="mb-3">
        Full Name: <input type="text" class="form-control" name="fullName" required>
      </div>
      <div class="mb-3">
        Address: <input type="text" class="form-control" name="address" required>
      </div>
      <div class="mb-3">
        Phone Number: <input type="text" class="form-control" name="phone" required>
      </div>
      <div class="mb-3">
        Email: <input type="email" class="form-control" name="email" required>
      </div>

      <h3 class="mt-4">Employment Information</h3>
      <div class="mb-3">
        Title: <input type="text" class="form-control" name="title" required>
      </div>
      <div class="mb-3">
        Department: <input type="text" class="form-control" name="department" required>
      </div>
      <div class="mb-3">
        Date of Hire: <input type="date" class="form-control" name="hireDate" required>
      </div>
      <div class="mb-3">
        Employment Status:<br>
        <div class="form-check form-check-inline">
          <input class="form-check-input" type="checkbox" name="status" value="Full Time">
          <label class="form-check-label">Full Time</label>
        </div>
        <div class="form-check form-check-inline">
          <input class="form-check-input" type="checkbox" name="status" value="Part Time">
          <label class="form-check-label">Part Time</label>
        </div>
        <div class="form-check form-check-inline">
          <input class="form-check-input" type="checkbox" name="status" value="Contractor">
          <label class="form-check-label">Contractor</label>
        </div>
        <div class="form-check form-check-inline">
          <input class="form-check-input" type="checkbox" name="status" value="Intern">
          <label class="form-check-label">Intern</label>
        </div>
        <div class="form-check form-check-inline">
          <input class="form-check-input" type="checkbox" name="status" value="Other">
          <label class="form-check-label">Other:</label>
          <input type="text" class="form-control form-control-sm d-inline-block w-auto" name="otherStatus">
        </div>
      </div>

      <h3 class="mt-4">Education</h3>
      <div class="mb-3">
        Highest Level of Education: <input type="text" class="form-control" name="educationLevel" required>
      </div>
      <div class="mb-3">
        Name of Institution: <input type="text" class="form-control" name="institution" required>
      </div>
      <div class="mb-3">
        Degree Earned: <input type="text" class="form-control" name="degree" required>
      </div>
      <div class="mb-3">
        Major/Field of Study: <input type="text" class="form-control" name="major" required>
      </div>
      <div class="mb-3">
        Graduation Date: <input type="date" class="form-control" name="gradDate" required>
      </div>

      <h3 class="mt-4">Professional Experience</h3>
      <div class="mb-3">
        Licenses: <input type="text" class="form-control" name="licenses">
      </div>
      <div class="mb-3">
        Previous Work Experience:
        <textarea class="form-control" name="experience" style="height: 150px;"></textarea>
      </div>

      <h3 class="mt-4">Emergency Contact Information</h3>
      <div class="mb-3">
        Full Name: <input type="text" class="form-control" name="emergencyName" required>
      </div>
      <div class="mb-3">
        Address: <input type="text" class="form-control" name="emergencyAddress" required>
      </div>
      <div class="mb-3">
        Phone Number: <input type="text" class="form-control" name="emergencyPhone" required>
      </div>
      <div class="mb-3">
        Cell Phone Number: <input type="text" class="form-control" name="emergencyCell" required>
      </div>
      <div class="mb-3">
        Relationship: <input type="text" class="form-control" name="relationship" required>
      </div>

      <h3 class="mt-4">Employee Signature</h3>
      <div class="mb-3">
        Signature: <input type="text" class="form-control" name="signature">
      </div>
      <div class="mb-3">
        Date: <input type="text" class="form-control" name="date">
      </div>

      <input type="submit" class="btn btn-primary" value="Submit">
    </form>
  </div>

  <script src="js/bootstrap.bundle.min.js"></script>
  <script src="form.js"></script>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Submitted Info</title>
  <link rel="stylesheet" href="form.css">
</head>
<body>
  <h1>SUBMITTED EMPLOYEE INFORMATION</h1>
  <hr>
  <div id="displayData"></div>

  <script>
    const data = JSON.parse(localStorage.getItem("employeeFormData"));
    const output = document.getElementById("displayData");

    if (data) {
      output.innerHTML = `
        <h3>Personal Information</h3>
        <p><strong>Name:</strong> ${data.fullName}</p>
        <p><strong>Address:</strong> ${data.address}</p>
        <p><strong>Phone:</strong> ${data.phone}</p>
        <p><strong>Email:</strong> ${data.email}</p>

        <h3>Employment Info</h3>
        <p><strong>Title:</strong> ${data.title}</p>
        <p><strong>Department:</strong> ${data.department}</p>
        <p><strong>Date of Hire:</strong> ${data.hireDate}</p>
        <p><strong>Status:</strong> ${data.status.join(", ") || data.otherStatus}</p>

        <h3>Education</h3>
        <p><strong>Level:</strong> ${data.educationLevel}</p>
        <p><strong>Institution:</strong> ${data.institution}</p>
        <p><strong>Degree:</strong> ${data.degree}</p>
        <p><strong>Major:</strong> ${data.major}</p>
        <p><strong>Graduation:</strong> ${data.gradDate}</p>

        <h3>Experience</h3>
        <p><strong>Licenses:</strong> ${data.licenses}</p>
        <p><strong>Work Experience:</strong> ${data.experience}</p>

        <h3>Emergency Contact</h3>
        <p><strong>Name:</strong> ${data.emergencyName}</p>
        <p><strong>Address:</strong> ${data.emergencyAddress}</p>
        <p><strong>Phone:</strong> ${data.emergencyPhone}</p>
        <p><strong>Cell:</strong> ${data.emergencyCell}</p>
        <p><strong>Relationship:</strong> ${data.relationship}</p>

        <h3>Signature</h3>
        <p>${data.signature} | ${data.date}</p>
      `;
    } else {
      output.innerHTML = "<p>No submitted data found.</p>";
    }
  </script>
</body>
</html>

document.getElementById("employeeForm").addEventListener("submit", function (e) {
    e.preventDefault();
    const form = e.target;
  
    const formData = {
      fullName: form.fullName.value,
      address: form.address.value,
      phone: form.phone.value,
      email: form.email.value,
      title: form.title.value,
      department: form.department.value,
      hireDate: form.hireDate.value,
      status: Array.from(form.querySelectorAll('input[name="status"]:checked')).map(cb => cb.value),
      otherStatus: form.otherStatus.value,
      educationLevel: form.educationLevel.value,
      institution: form.institution.value,
      degree: form.degree.value,
      major: form.major.value,
      gradDate: form.gradDate.value,
      licenses: form.licenses.value,
      experience: form.experience.value,
      emergencyName: form.emergencyName.value,
      emergencyAddress: form.emergencyAddress.value,
      emergencyPhone: form.emergencyPhone.value,
      emergencyCell: form.emergencyCell.value,
      relationship: form.relationship.value,
      signature: form.signature.value,
      date: form.date.value,
    };
  
    localStorage.setItem("employeeFormData", JSON.stringify(formData));
    window.location.href = "submitted.html";
  });
