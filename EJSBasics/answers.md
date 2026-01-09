1. In one sentence: What does res.render(view, data) do?
-res.render(view, data) renders a template (like EJS) with the given data and sends the resulting HTML to the client.
2. What is the difference between <%= %> and <%- %>?
-<%= %> outputs escaped HTML (safe), while <%- %> outputs unescaped HTML (raw).
3. Where does Express look for EJS templates (folder path)?
-Express looks for EJS templates in the views/ folder by default.