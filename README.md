# PersianScrollingDatePicker
pure JavaScript and Tailwind CSS Persian (Jalali) date picker with  scrolling style Created By Peymaan Abedinpour

![Persian (Jalali) date picker with  scrolling style Created By Peymaan Abedinpour](https://raw.githubusercontent.com/peymaanabedin/PersianScrollingDatePicker/main/persianScrollingdatepicker.jpg)

**Demo Link: ** [PersianScrollingDatePicker](https://peymaanabedin.github.io/PersianScrollingDatePicker-demo.html)


Welcome to the Scrolling Persian Date Picker project! This tool was created by **Peymaan Abedinpour** and is the **first Persian date picker with a scrolling style** built using pure JavaScript, jQuery, and TailwindCSS. Designed specifically for the Persian (Jalali) calendar, this date picker offers a smooth scrolling mechanism and an intuitive user interface for selecting dates, reminiscent of native iOS-style pickers. It is **fully optimized for mobile devices**, providing a seamless and user-friendly experience for all users interacting with the Persian calendar across all platforms.

#### Features

1.  **First Scrolling Style Persian Date Picker**: This is the pioneering date picker that introduces a scrolling interface for Persian dates, providing a unique and efficient way to select dates in the Jalali calendar format.
2.  **Mobile-Friendly Design**: The date picker is fully optimized for mobile devices, ensuring that users have a smooth and intuitive experience on smartphones and tablets. The touch-friendly interface and responsive design make it ideal for use on smaller screens.
3.  **Pure JavaScript Implementation**: No reliance on heavy libraries or frameworks. This project is lightweight and only requires jQuery and Jalaali.js for Persian date calculations.
4.  **TailwindCSS Styling**: The date picker is fully styled using TailwindCSS, ensuring a modern, responsive, and mobile-friendly design.
5.  **iOS-style Scrolling Picker**: An intuitive scrolling interface that mimics the native iOS date picker, allowing users to smoothly scroll through years, months, and days.
6.  **Persian Calendar Support**: Complete support for the Persian (Jalali) calendar, with accurate month lengths and date calculations.
7.  **Modal-Based UI**: The date picker appears in a modal window, providing a clean and focused user experience.

#### Getting Started

To use the Persian Date Picker in your project, follow these simple steps:

1.  **Include the Required Libraries**: Add the necessary scripts and stylesheets to your HTML file:

    `<script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
    <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet" />
    <link href="https://cdn.jsdelivr.net/npm/vazirmatn@33.0.3/Vazirmatn-font-face.min.css" rel="stylesheet" />
    <script src="https://cdn.jsdelivr.net/npm/jalaali-js/dist/jalaali.js"></script>`

2.  **Add the Date Picker Input Field**: Insert an input field into your HTML where you want the date picker to appear:

    `<input type="text" id="deliveryDate" class="block w-72 max-w-xs mx-auto p-3 text-center text-base border border-gray-300 rounded-lg shadow-sm cursor-pointer" readonly />`

3.  **Initialize the Persian Date Picker**: Use the provided JavaScript to initialize the date picker:


    `$(document).ready(function () {
      initializePersianDatePicker("deliveryDate");
    });`

#### Usage

Clicking on the input field will open the date picker modal. Users can scroll through the years, months, and days using a smooth, touch-friendly interface. Once the desired date is selected, clicking the "تایید" (Confirm) button will populate the input field with the selected date in the format `YYYY-MM-DD`.

#### Customization

The Persian Date Picker is highly customizable:

-   **Styling**: Adjust the appearance using TailwindCSS classes or your own custom styles.
-   **Date Range**: Modify the date range by changing the `getRange` function parameters in the JavaScript code.
-   **Event Handling**: Customize behavior by modifying or extending the JavaScript event listeners.

#### How It Works

The date picker dynamically creates a modal element and uses JavaScript to handle date selection and modal interactions. It uses the `jalaali-js` library for Persian date calculations and jQuery for DOM manipulation and event handling.

-   **iOS-Style Selector**: The `IosSelector` class simulates a scrolling selector with touch and mouse events to provide a smooth user experience.
-   **Dynamic Date Calculation**: The number of days in each month is calculated based on the selected year and month using the `jalaali.jalaaliMonthLength` function.

#### Contributing

We welcome contributions to enhance this project! Whether it's bug fixes, new features, or improvements, feel free to open an issue or submit a pull request on GitHub.

#### License

This project is open-source and available under the MIT License.

* * * * *

Feel free to explore the code, suggest improvements, and customize the Persian Date Picker to fit your needs. We hope this tool provides a useful and engaging date selection experience for your Persian calendar needs, especially on mobile devices!Welcome to the Persian Date Picker project! This tool was created by **Parsam** and is the **first Persian date picker with a scrolling style** built using pure JavaScript, jQuery, and TailwindCSS. Designed specifically for the Persian (Jalali) calendar, this date picker offers a smooth scrolling mechanism and an intuitive user interface for selecting dates, reminiscent of native iOS-style pickers. It is **fully optimized for mobile devices**, providing a seamless and user-friendly experience for all users interacting with the Persian calendar across all platforms.

#### Features

1.  **First Scrolling Style Persian Date Picker**: This is the pioneering date picker that introduces a scrolling interface for Persian dates, providing a unique and efficient way to select dates in the Jalali calendar format.
2.  **Mobile-Friendly Design**: The date picker is fully optimized for mobile devices, ensuring that users have a smooth and intuitive experience on smartphones and tablets. The touch-friendly interface and responsive design make it ideal for use on smaller screens.
3.  **Pure JavaScript Implementation**: No reliance on heavy libraries or frameworks. This project is lightweight and only requires jQuery and Jalaali.js for Persian date calculations.
4.  **TailwindCSS Styling**: The date picker is fully styled using TailwindCSS, ensuring a modern, responsive, and mobile-friendly design.
5.  **iOS-style Scrolling Picker**: An intuitive scrolling interface that mimics the native iOS date picker, allowing users to smoothly scroll through years, months, and days.
6.  **Persian Calendar Support**: Complete support for the Persian (Jalali) calendar, with accurate month lengths and date calculations.
7.  **Modal-Based UI**: The date picker appears in a modal window, providing a clean and focused user experience.

#### Getting Started

To use the Persian Date Picker in your project, follow these simple steps:

1.  **Include the Required Libraries**: Add the necessary scripts and stylesheets to your HTML file:

    html

    Copy code

    `<script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
    <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet" />
    <link href="https://cdn.jsdelivr.net/npm/vazirmatn@33.0.3/Vazirmatn-font-face.min.css" rel="stylesheet" />
    <script src="https://cdn.jsdelivr.net/npm/jalaali-js/dist/jalaali.js"></script>`

2.  **Add the Date Picker Input Field**: Insert an input field into your HTML where you want the date picker to appear:

    html

    Copy code

    `<input type="text" id="deliveryDate" class="block w-72 max-w-xs mx-auto p-3 text-center text-base border border-gray-300 rounded-lg shadow-sm cursor-pointer" readonly />`

3.  **Initialize the Persian Date Picker**: Use the provided JavaScript to initialize the date picker:

    javascript

    Copy code

    `$(document).ready(function () {
      initializePersianDatePicker("deliveryDate");
    });`

#### Usage

Clicking on the input field will open the date picker modal. Users can scroll through the years, months, and days using a smooth, touch-friendly interface. Once the desired date is selected, clicking the "تایید" (Confirm) button will populate the input field with the selected date in the format `YYYY-MM-DD`.

#### Customization

The Persian Date Picker is highly customizable:

-   **Styling**: Adjust the appearance using TailwindCSS classes or your own custom styles.
-   **Date Range**: Modify the date range by changing the `getRange` function parameters in the JavaScript code.
-   **Event Handling**: Customize behavior by modifying or extending the JavaScript event listeners.

#### How It Works

The date picker dynamically creates a modal element and uses JavaScript to handle date selection and modal interactions. It uses the `jalaali-js` library for Persian date calculations and jQuery for DOM manipulation and event handling.

-   **iOS-Style Selector**: The `IosSelector` class simulates a scrolling selector with touch and mouse events to provide a smooth user experience.
-   **Dynamic Date Calculation**: The number of days in each month is calculated based on the selected year and month using the `jalaali.jalaaliMonthLength` function.

#### Contributing

We welcome contributions to enhance this project! Whether it's bug fixes, new features, or improvements, feel free to open an issue or submit a pull request on GitHub.

#### License

This project is open-source and available under the MIT License.

* * * * *

Feel free to explore the code, suggest improvements, and customize the Persian Date Picker to fit your needs. We hope this tool provides a useful and engaging date selection experience for your Persian calendar needs, especially on mobile devices!

**My Email Address:** Peymaancrafts@gmail.com 
