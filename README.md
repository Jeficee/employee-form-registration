document.getElementById("employeeForm").addEventListener("submit", function (e) {
  e.preventDefault();
  const form = e.target;
  let isValid = true;

  // Check all required fields
  const requiredInputs = form.querySelectorAll("[required]");
  requiredInputs.forEach(input => {
    if (!input.value.trim()) {
      input.classList.add("is-invalid");
      input.classList.remove("is-valid");
      isValid = false;
    } else {
      input.classList.remove("is-invalid");
      input.classList.add("is-valid");
    }
  });

  if (!isValid) return;

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

  const output = document.getElementById("displayData");
  output.innerHTML = `
    <h3 class="mt-5">Submitted Data</h3>
    <h4>Personal Information</h4>
    <p><strong>Name:</strong> ${formData.fullName || "No input"}</p>
    <p><strong>Address:</strong> ${formData.address || "No input"}</p>
    <p><strong>Phone:</strong> ${formData.phone || "No input"}</p>
    <p><strong>Email:</strong> ${formData.email || "No input"}</p>

    <h4>Employment Info</h4>
    <p><strong>Title:</strong> ${formData.title || "No input"}</p>
    <p><strong>Department:</strong> ${formData.department || "No input"}</p>
    <p><strong>Date of Hire:</strong> ${formData.hireDate || "No input"}</p>
    <p><strong>Status:</strong> ${(formData.status.length > 0 ? formData.status.join(", ") : formData.otherStatus || "No input")}</p>

    <h4>Education</h4>
    <p><strong>Level:</strong> ${formData.educationLevel || "No input"}</p>
    <p><strong>Institution:</strong> ${formData.institution || "No input"}</p>
    <p><strong>Degree:</strong> ${formData.degree || "No input"}</p>
    <p><strong>Major:</strong> ${formData.major || "No input"}</p>
    <p><strong>Graduation:</strong> ${formData.gradDate || "No input"}</p>

    <h4>Experience</h4>
    <p><strong>Licenses:</strong> ${formData.licenses || "No input"}</p>
    <p><strong>Work Experience:</strong> ${formData.experience || "No input"}</p>

    <h4>Emergency Contact</h4>
    <p><strong>Name:</strong> ${formData.emergencyName || "No input"}</p>
    <p><strong>Address:</strong> ${formData.emergencyAddress || "No input"}</p>
    <p><strong>Phone:</strong> ${formData.emergencyPhone || "No input"}</p>
    <p><strong>Cell:</strong> ${formData.emergencyCell || "No input"}</p>
    <p><strong>Relationship:</strong> ${formData.relationship || "No input"}</p>

    <h4>Signature</h4>
    <p>${formData.signature || "No input"} | ${formData.date || "No input"}</p>
  `;
});