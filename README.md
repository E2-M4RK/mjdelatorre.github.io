<h1 align="center"><b>Mark Joseph Dela Torre</b></h1>

<p align="center">
  Personal Repository – Codes, Projects, and Experiments
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Status-Active-brightgreen" />
  <img src="https://img.shields.io/badge/Made%20with-Passion-ff69b4" />
</p>

---

This repository contains:

- Malalagyan din yan wait lang

---

```js
function showAlert(message, type = 'primary') {
  const alert = document.createElement('div');
  alert.className = `alert alert-${type} alert-dismissible fade show`;
  alert.innerHTML = `
    ${message}
    <button type="button" class="btn-close" data-bs-dismiss="alert"></button>
  `;
  document.body.appendChild(alert);
}
