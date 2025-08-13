# ♟️ Good Old Chess

![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)
![GitHub forks](https://img.shields.io/github/forks/MeethCodes/Good_Old_Chess?style=social)
![GitHub stars](https://img.shields.io/github/stars/MeethCodes/Good_Old_Chess?style=social)

A classic chess game with a clean, modern interface. This project delivers a timeless two-player chess experience directly in your browser, built with a focus on smooth gameplay and a robust component-based architecture.

---

## 📸 Preview

![A screenshot of the Good Old Chess game board in action.](./assets/temp_chess_pic.jpg)

---

## ✨ Features

* **Full Chess Ruleset:** Implements all standard rules including piece movements, captures, castling, and en passant.
* **Interactive UI:** A drag-and-drop interface for moving pieces across the board.
* **Move Validation:** The application strictly prevents illegal moves, ensuring fair play.
* **Game State Detection:** Automatically detects and announces check, checkmate, and stalemate conditions.
* **Responsive Design:** A clean and playable interface on both desktop and mobile devices.

---

## 💻 Tech Stack

* **Frontend:** React, HTML5, CSS3
* **Backend:** Node.js, Express.js
* **Development:** Git, GitHub

---

## 🚀 Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

Make sure you have Node.js and npm (Node Package Manager) installed on your system.
* You can download them here: [https://nodejs.org/](https://nodejs.org/)

### Installation & Setup

1.  **Fork the repository** and then clone your forked copy:
    ```sh
    git clone [https://github.com/your-username/Good_Old_Chess.git](https://github.com/your-username/Good_Old_Chess.git)
    cd Good_Old_Chess
    ```

2.  **Install Client Dependencies:** Navigate to the client directory and install the required packages.
    ```sh
    cd client
    npm install
    ```

3.  **Install Server Dependencies:** From the root directory, navigate to the server and install its packages.
    ```sh
    cd ../server
    npm install
    ```

### Running the Application

You will need to run the frontend and backend in separate terminals.

1.  **Start the Backend Server:** In your first terminal, from the `server` directory, run:
    ```sh
    npm start
    ```
    The server will typically start on `http://localhost:5000`.

2.  **Start the Frontend Client:** In a second terminal, from the `client` directory, run:
    ```sh
    npm start
    ```
    The application will open automatically in your browser at `http://localhost:3000`.

---

## 🤝 How to Contribute

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**. We follow the standard GitHub Fork & Pull Request workflow.

1.  **Fork** the project.
2.  Create your feature branch (`git checkout -b feature/AmazingFeature`).
3.  Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4.  Push to the branch (`git push origin feature/AmazingFeature`).
5.  Open a **Pull Request** against the `main` branch for review.

---

## 📜 License

Distributed under the MIT License. See the `LICENSE` file for more information.

---

##  Acknowledgments

* Project created and maintained by **Meeth** and **Om**.
