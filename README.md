# Currency-Converter
A **Currency Converter** that integrates both a **Currency Exchange API** and a **Flag API** provides an enhanced, user-friendly experience by offering real-time exchange rates and dynamically displaying country flags corresponding to selected currencies. This web-based application is built using **HTML**, **CSS**, and **JavaScript**, making it an engaging tool for users to convert values between different currencies while also visualizing the country associated with each currency through flags.

### HTML Structure:
The **HTML** forms the backbone of the currency converter, defining the layout and structure of the application. It includes key elements like input fields for users to enter the amount they want to convert, dropdown menus for selecting the source (from) and target (to) currencies, a button to trigger the conversion, and a space to display the conversion results. Each dropdown for currency selection is paired with an image tag, where the flag of the corresponding currency is dynamically updated. The clean and minimal HTML structure ensures that the interface is easy to navigate for users.

### CSS Styling:
The **CSS** ensures that the application is visually appealing and responsive across various devices. The design focuses on a clean and organized layout where input fields, dropdowns, and buttons are neatly styled. Special attention is given to the flags, making sure they are well-sized and visually aligned with the currency selectors. The results section, which displays the conversion outcome, is clearly highlighted, ensuring that users can easily view the converted amount.

### JavaScript Functionality:
JavaScript handles all the functionality of the currency converter. It interacts with two main APIs:
- **Currency API**: This API provides real-time exchange rates for different currencies. When the user enters an amount, selects the "From" and "To" currencies, and clicks the convert button, JavaScript sends a request to this API to fetch the latest exchange rate. The retrieved exchange rate is then used to calculate and display the converted amount on the screen.
- **Flag API**: JavaScript also interacts with the Flag API to display the correct flag for each selected currency. When the user selects a currency from the dropdown, JavaScript updates the corresponding flag image by fetching the country code from the Flag API and dynamically setting the image source URL. This adds a visual layer to the conversion process, making the interface more engaging and informative.

### Real-Time Exchange Rates and Flag Display:
The **real-time exchange rates** are fetched from the Currency API whenever the user performs a conversion. This ensures that users get up-to-date rates, making the conversion accurate. Meanwhile, the **Flag API** enhances the visual experience by displaying the correct country flag associated with each currency. As users change their currency selections, the corresponding flags are dynamically updated, making it easier for users to recognize the currencies they are dealing with. For example, selecting the "USD" currency will display the flag of the United States, while selecting "INR" will show the Indian flag.

### Additional Features:
- **Swap Button**: The converter often includes a swap button that allows users to reverse the "From" and "To" currencies with a single click. This feature also swaps the associated flags, enhancing the convenience and interactivity of the tool.
- **Auto Update on Page Load**: When the page is loaded or refreshed, the input amount is set to 1 by default, and an automatic conversion is performed using the default currency selections. This makes the converter ready for use immediately without additional input from the user.
- **User-Friendly Input Validation**: JavaScript ensures that the user input is valid (i.e., numeric values) and automatically sets the amount to 1 if no value is entered, ensuring smooth user experience.

### Conclusion:
The **Currency Converter** with integrated **Currency API** and **Flag API** provides a robust, user-friendly, and visually appealing tool for converting currencies in real time. By displaying country flags alongside currency selections, the application enhances the user experience, making it more intuitive and engaging. The use of **HTML**, **CSS**, and **JavaScript** showcases important web development concepts such as API integration, dynamic content updates, DOM manipulation, and responsive design. This project is an excellent demonstration of how to combine APIs to create a practical and interactive web application.
