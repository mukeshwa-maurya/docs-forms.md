# Update Form API

Updates an existing form based on the given ID.

---

## HTTP Method

`PUT /api/forms/{id}`

---

## Parameters

- `id`: The unique identifier of the form to update  
  **Example:** `fec6d87d-5906-4a76-bda6-0ccab8642a06`

---

## Sample Request

```json
{
  "formName": "Customer Feedback Form",
  "formType": "HTML FORM",
  "definition": "{\"logoPosition\":\"right\",\"pages\":[{\"name\":\"page1\",\"elements\":[{\"type\":\"text\",\"name\":\"question1\",\"id\":\"sq_514\"},{\"type\":\"text\",\"name\":\"question2\",\"id\":\"sq_514\"},{\"type\":\"text\",\"name\":\"question3\",\"id\":\"sq_514\"}]}]}",
  "themeID": null,
  "ownerID": "3fa85f64-5717-4562-b3fc-2c963f66afa6",
  "loginRequired": true,
  "submitMethod": "Incremental",
  "submitMode": "Multiple"
}
