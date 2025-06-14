<div class="mb-3">
    <label class="form-label d-block">Employment Status</label>
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
    <label class="form-label">Highest Level of Education</label>
    <input type="text" class="form-control" name="educationLevel" required>
    <div class="valid-feedback">✅ Looks good!</div>
    <div class="invalid-feedback">❌ Please enter your highest education level.</div>
  </div>
  <div class="mb-3">
    <label class="form-label">Name of Institution</label>
    <input type="text" class="form-control" name="institution" required>
    <div class="valid-feedback">✅ Looks good!</div>
    <div class="invalid-feedback">❌ Please provide the institution name.</div>
  </div>
  <div class="mb-3">
    <label class="form-label">Degree Earned</label>
    <input type="text" class="form-control" name="degree" required>
    <div class="valid-feedback">✅ Looks good!</div>
    <div class="invalid-feedback">❌ Please enter the degree earned.</div>
  </div>
  <div class="mb-3">
    <label class="form-label">Major/Field of Study</label>
    <input type="text" class="form-control" name="major" required>
    <div class="valid-feedback">✅ Looks good!</div>
    <div class="invalid-feedback">❌ Please provide your field of study.</div>
  </div>
  <div class="mb-3">
    <label class="form-label">Graduation Date</label>
    <input type="date" class="form-control" name="gradDate" required>
    <div class="valid-feedback">✅ Looks good!</div>
    <div class="invalid-feedback">❌ Please enter graduation date.</div>
  </div>

  <h3 class="mt-4">Professional Experience</h3>
  <div class="mb-3">
    <label class="form-label">Licenses</label>
    <input type="text" class="form-control" name="licenses">
  </div>
  <div class="mb-3">
    <label class="form-label">Previous Work Experience</label>
    <textarea class="form-control" name="experience" style="height: 150px;"></textarea>
  </div>

  <h3 class="mt-4">Emergency Contact Information</h3>
  <div class="mb-3">
    <label class="form-label">Full Name</label>
    <input type="text" class="form-control" name="emergencyName" required>
    <div class="valid-feedback">✅ Looks good!</div>
    <div class="invalid-feedback">❌ Please provide emergency contact name.</div>
  </div>
  <div class="mb-3">
    <label class="form-label">Address</label>
    <input type="text" class="form-control" name="emergencyAddress" required>
    <div class="valid-feedback">✅ Looks good!</div>
    <div class="invalid-feedback">❌ Please provide emergency contact address.</div>
  </div>
  <div class="mb-3">
    <label class="form-label">Phone Number</label>
    <input type="text" class="form-control" name="emergencyPhone" required>
    <div class="valid-feedback">✅ Looks good!</div>
    <div class="invalid-feedback">❌ Please provide emergency contact phone number.</div>
  </div>
  <div class="mb-3">
    <label class="form-label">Cell Phone Number</label>
    <input type="text" class="form-control" name="emergencyCell" required>
    <div class="valid-feedback">✅ Looks good!</div>
    <div class="invalid-feedback">❌ Please provide emergency contact cell number.</div>
  </div>
  <div class="mb-3">
    <label class="form-label">Relationship</label>
    <input type="text" class="form-control" name="relationship" required>
    <div class="valid-feedback">✅ Looks good!</div>
    <div class="invalid-feedback">❌ Please state your relationship to the emergency contact.</div>
  </div>

  <h3 class="mt-4">Employee Signature</h3>
  <div class="mb-3">
    <label class="form-label">Signature</label>
    <input type="text" class="form-control" name="signature">
  </div>
  <div class="mb-3">
    <label class="form-label">Date</label>
    <input type="text" class="form-control" name="date">
  </div>

  <input type="submit" class="btn btn-primary" value="Submit">
</form>