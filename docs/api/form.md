---
id: form
title: <Form />
---

Form is a small wrapper around an HTML `<form>` element that automatically hooks into Formik's `handleSubmit`. All other props are passed directly through to the DOM node.

```jsx
// so...
<Form />

// is identical to this...
<form onSubmit={formikProps.handleSubmit} {...props} />
```

