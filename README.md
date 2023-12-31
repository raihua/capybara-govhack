# Table of Contents

- [Welcome to ElectroForesight Dashboard](#welcome-to-electroforesight-dashboard)
  - [Project Overview](#project-overview)
  - [Getting Started](#getting-started)
  - [Website Instructions](#website-instructions)
  - [Technology Stack](#technology-stack)
  - [Evidence of Work](#evidence-of-work)
    - [Wireframe](#wireframe)
    - [Interpreting Data from Machine Learning ARIMA Model](#interpreting-data-from-machine-learning-arima-model)
    - [Forecast Generation with Python](#forecast-generation-with-python)
    - [Video Editing](#video-editing)
    - [Deployment](#deployment)
  - [Team Members](#team-members)

---

# Welcome to ElectroForesight Dashboard

![image](https://github.com/raihua/capybara-govhack/assets/115681947/633f037f-5f85-4e0b-8500-544275596c1c)

#### By Team Capybara-govhack

## Project Overview
In the current landscape with immense growth potential for Electric Vehicles (EVs), there is a growing need for more information regarding the benefits and challenges they bring. As a response, our team has developed the ElectroForesight Dashboard. Our objective is to illustrate a range of external factors influencing the future quantity of EVs.

We have employed data modeling to predict the impact of GDP growth on the increase in electric car sales. Furthermore, we have explored how the rising number of electric vehicles might affect the power grid's load. Employing two models based on AEMO's data, we've identified that 10 am and 7 pm are peak electricity usage hours due to behavioral patterns. We have devised separate models for Day and Night scenarios to depict the projected impact of growing EV electricity demand on the grid's power consumption. Based on our assumptions, assuming EV charging habits remain consistent with the current nighttime charging behavior in the models, the demand could surpass the current grid capability earlier than during daytime charging.

Additionally, we have pondered the relationship between EV development and energy storage, yielding valuable insights into sustainable energy supply considerations.


## Getting started
Visit us at capybara-govhack.vercel.app or follow these steps to get started:
or
Clone from Github
```
git clone https://github.com/raihua/capybara-govhack.git
yarn
yarn start
```

## Website Instructions
Each page of our website displays the count of electric vehicles and buttons to increase or decrease the factors that influence them. Explore the insights and interact with the data to gain a deeper understanding of the impact of external factors on EVs.

Explore our ElectroForesight Dashboard and discover the future of Electric Vehicles!

## Technology Stack

The ElectroForesight Dashboard is built on a robust technology stack that combines various tools and libraries to provide a seamless and efficient user experience.

- **Material UI V5:** We've utilized Material UI V5, a popular and versatile UI framework, to create visually appealing and responsive user interfaces.

- **React Hooks API:** Leveraging the power of React Hooks, our application benefits from improved code organization and reusability, making development smoother and more efficient.

- **Redux & React Context API:** For effective state management, we've harnessed the capabilities of both Redux and the React Context API. This ensures centralized and consistent data handling throughout the application.

- **Redux Toolkit:** Our team has chosen Redux Toolkit, a comprehensive package, to simplify and streamline the process of managing state, actions, and reducers in Redux.

- **React Router:** Navigation routing is seamless and intuitive thanks to React Router. Users can move through different sections of the dashboard with ease and speed.

- **Support for react-scripts:** By integrating with react-scripts, we've enabled a straightforward development experience, allowing for quick testing and deployment.

- **Code Splitting:** To enhance performance, our application utilizes code splitting techniques, ensuring that only necessary components are loaded, minimizing initial loading times.

- **CSS-in-JS:** We've adopted CSS-in-JS for styling, enabling a component-based approach to styling that ensures encapsulation and maintainability.



## Evidence of Work
### Wireframe

![efc2caf8bb2a3aac2d79bcdde9556594](https://github.com/raihua/capybara-govhack/assets/115681947/15cc49b4-85e5-4628-a733-e4b6e89354bc)
![c379cad6d38049d7949375b7207df9d9](https://github.com/raihua/capybara-govhack/assets/115681947/4b135b87-1cf8-4e69-bdbe-72a7c46cf7e0)

### Interpreting Data from Machine Learning ARIMA Model
<img width="895" alt="Screenshot 2023-08-20 at 4 14 13 pm" src="https://github.com/raihua/capybara-govhack/assets/55374648/de448846-cc72-484e-a9b4-967b7d7675dd">
![USGDPEV-forecast](https://github.com/raihua/capybara-govhack/assets/55374648/a7784471-f59f-4761-8032-9b2e031ca81f)

### Forecast Generation with Python
You can use the Forecast Generator tool by running it in Python. Make sure to adjust the date ranges for the periods you want to forecast and change the file name to the CSV file you wish to read. Also, ensure that you modify the export file name to prevent overriding existing files.

### Video editing
![editing video](https://github.com/raihua/capybara-govhack/assets/55374648/5c791a74-cbce-4f92-9733-1270567acc86)

### Deployment
<img width="1395" alt="Screenshot 2023-08-20 at 4 09 40 pm" src="https://github.com/raihua/capybara-govhack/assets/55374648/ebb6a45c-d83a-407c-a02a-d73bb0d1a139">

## Team members
- Thomas Keo
- Hanqing Zhao
- Thenul Premadasa
- Peter Trinh
- Patrick Li


Feel free to explore our collaborative effort, the ElectroForesight Dashboard, and join us in shaping the future of Electric Vehicles!
