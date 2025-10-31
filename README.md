# PlantCare AI

PlantCare AI is an intelligent application designed to help farmers and plant enthusiasts diagnose plant diseases, receive AI-generated care plans, and participate in a marketplace for fresh produce.

## ✨ Features

*   **AI-Powered Disease Diagnosis:** Upload an image of a plant to get an AI-powered diagnosis of diseases.
*   **Customized 7-Day Care Plans:** Receive a detailed 7-day care plan tailored to the diagnosed disease.
*   **Marketplace:** A platform for farmers to list their produce and for users to buy fresh, local products.
*   **Track Your Plants:** Keep a digital record of your plants, their health status, and care history.
*   **User Authentication:** Secure user authentication and profile management.
*   **List and Manage Produce:** Farmers can easily list their produce for sale and manage their listings.

## 🚀 Tech Stack

### Frontend

*   **Framework:** [Next.js](https://nextjs.org/)
*   **Language:** [TypeScript](https://www.typescriptlang.org/)
*   **Styling:** [Tailwind CSS](https://tailwindcss.com/)
*   **Animation:** [Framer Motion](https://www.framer.com/motion/)
*   **UI Components:** [Shadcn/UI](https://ui.shadcn.com/)
*   **Form Management:** [React Hook Form](https://react-hook-form.com/) & [Zod](https://zod.dev/)
*   **HTTP Client:** [Axios](https://axios-http.com/)

### Backend

*   **Framework:** [FastAPI](https://fastapi.tiangolo.com/)
*   **Language:** [Python](https://www.python.org/)
*   **Database:** [MongoDB](https://www.mongodb.com/)
*   **Server:** [Uvicorn](https://www.uvicorn.org/)
*   **Authentication:** [python-jose](https://python-jose.readthedocs.io/en/latest/), [passlib](https://passlib.readthedocs.io/en/stable/), [bcrypt](https://pypi.org/project/bcrypt/)

## 🏁 Getting Started

Follow these instructions to get a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

*   [Node.js](https://nodejs.org/en/) (v18 or later)
*   [Yarn](https://classic.yarnpkg.com/en/docs/install)
*   [Python](https://www.python.org/downloads/) (v3.9 or later)
*   [MongoDB](https://www.mongodb.com/try/download/community)

### Installation

1.  **Clone the repository:**

    ```bash
    git clone https://github.com/your-username/ise-ke-hack.git
    cd ise-ke-hack
    ```

2.  **Install frontend dependencies:**

    ```bash
    cd frontend
    yarn install
    ```

3.  **Install backend dependencies:**

    ```bash
    cd ../Backend
    pip install -r requirements.txt
    ```

### Running the Application

1.  **Start the frontend development server:**

    From the `frontend` directory, run:

    ```bash
    yarn dev
    ```

    The frontend will be available at [http://localhost:3000](http://localhost:3000).

    **Note:** You can log in with demo credentials: **Phone: 1234567890**, **Password: 12345678**.

2.  **Start the backend server:**

    From the `Backend` directory, run:

    ```bash
    uvicorn main:app --reload
    ```

    The backend API will be available at [http://localhost:8000](http://localhost:8000).

## 📂 Folder Structure

```
ise-ke-hack/
├── Backend/
│   ├── app/
│   │   ├── api/
│   │   ├── core/
│   │   ├── db/
│   │   ├── middleware/
│   │   ├── models/
│   │   └── utils/
│   ├── main.py
│   └── requirements.txt
└── frontend/
    ├── public/
    ├── src/
    │   ├── app/
    │   │   ├── (dashboard)/
    │   │   └── auth/
    │   ├── components/
    │   ├── hooks/
    │   └── lib/
    ├── next.config.js
    └── package.json
```

## 🤝 Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1.  Fork the Project
2.  Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3.  Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4.  Push to the Branch (`git push origin feature/AmazingFeature`)
5.  Open a Pull Request
