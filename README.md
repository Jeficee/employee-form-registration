<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Employee Information Form</title>
  <link rel="stylesheet" href="css/bootstrap.min.css">
</head>
<body>
  <div class="container mt-5">
    <h1 class="text-center">EMPLOYEE INFORMATION FORM</h1>
    <hr><form id="employeeForm" novalidate>
  <h3 class="mt-4">Personal Information</h3>
  <div class="mb-3">
    <label class="form-label">Full Name</label>
    <input type="text" class="form-control" name="fullName" required>
    <div class="valid-feedback">✅ Looks good!</div>
    <div class="invalid-feedback">❌ Please provide your full name.</div>
  </div>
  <div class="mb-3">
    <label class="form-label">Address</label>
    <input type="text" class="form-control" name="address" required>
    <div class="valid-feedback">✅ Looks good!</div>
    <div class="invalid-feedback">❌ Please provide your address.</div>
  </div>
  <div class="mb-3">
    <label class="form-label">Phone Number</label>
    <input type="text" class="form-control" name="phone" required>
    <div class="valid-feedback">✅ Looks good!</div>
    <div class="invalid-feedback">❌ Please provide a phone number.</div>
  </div>
  <div class="mb-3">
    <label class="form-label">Email</label>
    <input type="email" class="form-control" name="email" required>
    <div class="valid-feedback">✅ Looks good!</div>
    <div class="invalid-feedback">❌ Please provide a valid email.</div>
  </div>

  <h3 class="mt-4">Employment Information</h3>
  <div class="mb-3">
    <label class="form-label">Title</label>
    <input type="text" class="form-control" name="title" required>
    <div class="valid-feedback">✅ Looks good!</div>
    <div class="invalid-feedback">❌ Please provide a title.</div>
  </div>
  <div class="mb-3">
    <label class="form-label">Department</label>
    <input type="text" class="form-control" name="department" required>
    <div class="valid-feedback">✅ Looks good!</div>
    <div class="invalid-feedback">❌ Please provide a department.</div>
  </div>
  <div class="mb-3">
    <label class="form-label">Date of Hire</label>
    <input type="date" class="form-control" name="hireDate" required>
    <div class="valid-feedback">✅ Looks good!</div>
    <div class="invalid-feedback">❌ Please provide the date of hire.</div>
  </div>
  <!-- You can continue adding similar blocks with validation messages -->

  <input type="submit" class="btn btn-primary" value="Submit">
</form>

  </div>  <script src="js/bootstrap.bundle.min.js"></script>  <script>
    (function () {
      const form = document.getElementById("employeeForm");

      form.addEventListener("submit", function (e) {
        if (!form.checkValidity()) {
          e.preventDefault();
          e.stopPropagation();
        }
        form.classList.add("was-validated");
      }, false);
    })();
  </script></body>
</html>