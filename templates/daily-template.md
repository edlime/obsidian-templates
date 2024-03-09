---
creation date: <% tp.file.creation_date() %>
steps: 
sleep: 
mood: 
energy: 
---
# <% moment(tp.file.title,'YYYY-MM-DD').format("dddd, MMMM DD, YYYY") %>

[[<% fileDate = moment(tp.file.title, 'YYYY-MM-DD').subtract(1, 'd').format('YYYY-MM-DD') %>|<< Yesterday]] | [[<% fileDate = moment(tp.file.title, 'YYYY-MM-DD').add(1, 'd').format('YYYY-MM-DD') %>|Tomorrow >>]]

## Weather

<%*
const weather = await requestUrl('https://wttr.in/<your-target-city>?format=%l:+%c+%C+%t+feels+like+%f%5CnTime:+++++%T%5CnSunrise:++%S%5CnSunset:+++%s%5CnMoon:+++++%m%5CnWind:+++++%w%5CnRainfall:+%p%5CnHumidity:+%h%5Cn')
tR += weather.text
%>


## Today's Tasks

- [ ] to do
- [ ] to do

## Schedule

| **Time** | **Planned** | **Actual** |
| -------- | ----------- | ---------- |
| 07:00    |             |            |
| 08:00    |             |            |
| 09:00    |             |            |
| 10:00    |             |            |
| 11:00    |             |            |
| 12:00    |             |            |
| 13:00    |             |            |
| 14:00    |             |            |
| 15:00    |             |            |
| 16:00    |             |            |
| 17:00    |             |            |
| 18:00    |             |            |
| 19:00    |             |            |
| 20:00    |             |            |
| 21:00    |             |            |
| 22:00    |             |            |
| 23:00    |             |            |

## Logs

- Log 1


## End of Day Notes

### I'm proud that...

- 

### I'm grateful that...

- 
