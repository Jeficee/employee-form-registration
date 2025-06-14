<script>
  document.addEventListener("DOMContentLoaded", function () {
    const form = document.getElementById("employeeForm");

    form.addEventListener("submit", function (e) {
      e.preventDefault();
      let isValid = true;

      const inputs = form.querySelectorAll("input, textarea, select");

      inputs.forEach(input => {
        if (input.hasAttribute("required")) {
          if (!input.value.trim()) {
            input.classList.remove("is-valid");
            input.classList.add("is-invalid");
            isValid = false;
          } else {
            input.classList.remove("is-invalid");
            input.classList.add("is-valid");
          }
        }
      });

      if (isValid) {
        // 👇 Collect and store form data
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

        alert("Form submitted successfully!");
        form.reset();
        form.querySelectorAll(".is-valid").forEach(el => el.classList.remove("is-valid"));
      }
    });

    // Live validation while typing
    const requiredFields = form.querySelectorAll("input[required], textarea[required]");

    requiredFields.forEach(input => {
      input.addEventListener("input", function () {
        if (input.value.trim()) {
          input.classList.remove("is-invalid");
          input.classList.add("is-valid");
        } else {
          input.classList.remove("is-valid");
          input.classList.add("is-invalid");
        }
      });
    });
  });
</script>