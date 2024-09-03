<a name="readme-top"></a>

<div align="center">
  <br/>

  <h3><b>Podcaster</b></h3>

</div>

<!-- TABLE OF CONTENTS -->

# 📗 Table of Contents

- [📖 About the Project](#about-project)
  - [🛠 Built With](#built-with)
    - [Tech Stack](#tech-stack)
    - [Key Features](#key-features)
  - [🚀 Live Demo](#live-demo)
- [💻 Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Setup](#setup)
  - [Install](#install)
  - [Usage](#usage)
  - [Run tests](#run-tests)
  - [Deployment](#deployment)
- [👥 Authors](#authors)
- [🤝 Contributing](#contributing)
- [⭐️ Show your support](#support)
- [🙏 Acknowledgements](#acknowledgements)
- [📝 License](#license)

<!-- PROJECT DESCRIPTION -->

# 📖 Podcaster<a name="about-project"></a>


**Podcaster** genera tu podcast usando IA.


## 🛠 Built With <a name="built-with"></a>

### Tech Stack <a name="tech-stack"></a>

<details>
  <summary>Client</summary>
  <ul>
    <li><a href="https://nextjs.org/">Next.js</a></li>
  </ul>
</details>

<details>
  <summary>Server</summary>
  <ul>
    <li><a href="https://openai.com/">OpenAI</a></li>
  </ul>
</details>

<details>
<summary>Database</summary>
  <ul>
    <li><a href="https://clerk.com/">Clerk</a></li>
  </ul>
</details>

<!-- Features -->

### Key Features <a name="key-features"></a>

- **Machine learning**
- **Process Automation**

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- LIVE DEMO -->

## 🚀 Live Demo <a name="live-demo"></a>


- [Podcaster](https://podcaster-zeta.vercel.app/)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- GETTING STARTED -->

## 💻 Getting Started <a name="getting-started"></a>

To get a local copy up and running, follow these steps.

### Prerequisites

In order to run this project you need:

### Setup

Clone this repository to your desired folder:

```sh
  cd my-folder
  git clone git@github.com:franclobo/podcaster.git
```

### Install

Install this project with:

```sh
  cd podcaster
  npm install
```

### Usage

To run the project, execute the following command:


```sh
  npm run dev
```

### Enviroment Variables

Create an account in [OpenAI](https://openai.com/) and get your OPENAI_API_KEY.
Create an account in [Convex](https://www.convex.dev/) and get your CONVEX_DEPLOYMENT and CONVEX_URL.
Create an account in [Clerk](https://clerk.com/) and get your CLERK_SECRET_KEY, CLERK_WEBHOOK_SECRET and CLERK_PUBLISHABLE_KEY.

Create a `.env` file in the root of the project and add the following variables:

```sh
  CONVEX_DEPLOYMENT=YOUR_DEPLOYMENT

  NEXT_PUBLIC_CONVEX_URL=YOUR_URL

  NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=YOUR_PUBLISHABLE_KEY
  CLERK_SECRET_KEY=YOUR_SECRET_KEY
  CLERK_WEBHOOK_SECRET=YOUR_WEBHOOK_SECRET
  NEXT_PUBLIC_CLERK_SIGN_IN_URL='sign-in'
  NEXT_PUBLIC_CLERK_SIGN_UP_URL='sign-up'

  OPENAI_API_KEY=YOUR_API_KEY
```

### Deployment

You can deploy this project using:

- Versel

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- AUTHORS -->

## 👥 Authors <a name="authors"></a>



## 👤 Francisco Borja

- GitHub: [@franclobo](https://github.com/franclobo)

- Twitter: [@pancho2788](https://twitter.com/Pancho2788)

- LinkedIn: [Francisco Borja](https://www.linkedin.com/in/francisco-borja-lobato/)


<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- CONTRIBUTING -->

## 🤝 Contributing <a name="contributing"></a>

Contributions, issues, and feature requests are welcome!

Feel free to check the [issues page](../../issues/).

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- SUPPORT -->

## ⭐️ Show your support <a name="support"></a>

> Write a message to encourage readers to support your project

If you like this project give it a ⭐️!

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ACKNOWLEDGEMENTS -->

## 🙏 Acknowledgments <a name="acknowledgements"></a>

> Give credit to everyone who inspired your codebase.

I would like to thank [JavaScript Mastery](https://www.youtube.com/watch?v=zfAb95tJvZQ&list=WL&index=55) for the inspiration for this project.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- LICENSE -->

## 📝 License <a name="license"></a>

This project is [MIT](./LICENSE) licensed.

<p align="right">(<a href="#readme-top">back to top</a>)</p>
