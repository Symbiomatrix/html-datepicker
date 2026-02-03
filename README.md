# html-datepicker
Date picker that's convenient for both mouse and finger users.

## Features
### V2
- D/M/Y thumbwheel of sorts - pressing and dragging day / month / year up or down anywhere in the page will change the value. Drag is sticky for precision.
- Mousewheel scrolling is also supported and quite speedy for pc master race.
- Ensures validity of dates, but will remember the day the user picked regardless - for example, selecting 31 on a january, then moving to february will show 28/02, but changing month again will move the day dial back to 31.
### V3
- Double click to edit value by typing.
- Smart type year - entering two digits will select a viable year from the range which ends with said digits (99 -> 1999, 20 -> 2020),
  if there are multiple matches will default to current century; same thing with 3 digits, ambiguity goes to current millennium (999 -> 1999, if range is 1000-3000 then 999 -> 2999).
- Arrow keys when in focus move between dmy and +-1 to value.

<img width="384" height="380" alt="image" src="https://github.com/user-attachments/assets/f219bcb7-636a-42d4-970d-e0407b41a161" />
