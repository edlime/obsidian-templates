---
<%*
   let title = tp.file.title;
   if (title.startsWith('Untitled')) {
      title = await tp.system.prompt('');
      await tp.file.rename(`${title}`);
   }
-%>
creation date: <% tp.file.creation_date() %>
type: person
email: 
location:
aliases:
---

# <%* tR += `${title}` %>

## Profile

| **Category**       | **Value** |
| ------------------ | --------- |
| Nickname           |           |
| Other name         |           |
| Birthday           |           |
| Phone              |           |
| Education          |           |
| Company            |           |
| Date first met     |           |
| Location first met |           |


## Interests

- x,y,z

## Fun Facts

- 

## Social media

- LinkedIn
- Facebook
- Instagram
- Twitter
- TikTok