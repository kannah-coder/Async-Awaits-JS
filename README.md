# Async-Awaits-JS
# Async Chores Simulation

This project demonstrates **JavaScript async/await** with **Promises** using a simple chore simulation.  

## Features
- `walkDog()` → simulates walking the dog (resolves after 2.5s)
- `cleanKitchen()` → simulates cleaning the kitchen (may reject)
- `takeOutTrash()` → simulates taking out the trash (may reject)
- `doChores()` → async function that calls all chores sequentially using `await` and handles errors with `try/catch`.

## How to Run
1. Open the HTML file in your browser.
2. Open browser console (F12 or right-click → Inspect → Console).
3. You will see the result of each chore logged in order.

## Notes
- `async` makes a function return a **Promise**.
- `await` makes an async function **wait for the Promise to resolve/reject**.
- Errors are caught using **try/catch** blocks.

## Future Improvements
- Add UI buttons to start chores interactively.
- Display results
- dynamically on the page instead of the console.


Async_Await/
│
├── async_await.html 
└──  async1.html          


