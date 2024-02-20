---
<%*
   let title = tp.file.title;
   if (title.startsWith('Untitled')) {
      title = await tp.system.prompt('');
      await tp.file.rename(tp.date.now("YYYY-MM-DD")+"-"+`${title}`);
   }
-%>
date: <% tp.file.creation_date() %>
type: meeting
company: 
summary: " "
---
# [[<% tp.date.now("YYYY-MM-DD")+" "+`${title}` %>]]


**Attendees**: 
- 

## Agenda
- 

## Notes
- 

## Action items

- [ ] Task 1
- [ ] Task 2


