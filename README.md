# Magic Number - Daily Increment

This is a very straightforward app based on a budgeting principle called the "Magic Number".

Long story short, you take your yearly salary and subtract yearly and monthly expenses (i.e. rent). You then divide that number by 12, for the months in a year, and again in 30, for the days in a month. You then "allot" yourself that amount of money to spend in a given day.

## MVP

The app is a very simple counter app, with some slight tweaks. You will be given your allotted amount of money, `MN`, every day. However, it will only trigger when you open the app (if you forget to open the app, that's on you!) That number can also be inserted at any time, no calculations necessary.

Whenever you spend money, you deduct it with a particular cost and a reason, i.e. `-$4, coffee` and it will deduct that from your magic number.

That's it!

### Features

- [] Daily increment that triggers once a day

## Future Goals

Whether these things ever happen depends on how much I actually want to work on this. I just don't want to keep using pen/paper, despite it being a little more fulfilling. Easier to have my phone on hand!

- The first thing will be to make the UI a lot more than a basic UI.
- Then some smaller features...
    - Configure your own timezone
    - Prevent changing the magic number more than once a week (arbitrary time)
    - Deduct multiple things at once
- Set some sort of negative balance, i.e. you can go $20 below $0 and not get a severe warning
- A way to set aside money from your balance, such as spending $15 of your daily allotment that stores somewhere else, so you can very simply manage a small savings balance
    - Targeted goals would be great for this, i.e. "spending" $10 6 days a week for a new Kirby game and having multiple goals going at once
- Calculating the number
    - This is a little complex, and requires potentially private information. Likely better to just calculate it in a spreadsheet.

We just have to make sure this doesn't turn into some other budgeting app. Nothing complicated, just straightforward options.

## Contributing

If you want to contribute... reach out to me here on GitHub, on [Twitter](http://www.twitter.com/Mobkinz78), or [Instagram](http://www.instagram.com/markbacon78)