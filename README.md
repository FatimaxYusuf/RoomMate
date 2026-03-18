# RoomMate — Open Source Hotel Reservation System

![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)
![Java](https://img.shields.io/badge/Java-17-orange.svg)
![Status](https://img.shields.io/badge/Status-Phase%201-blue.svg)

RoomMate is a free and open-source hotel reservation system that enables users to search for available rooms, make bookings, and manage reservations efficiently. The system was originally developed as part of the ITSE305 course at the University of Bahrain and is now extended as an open-source project under ITSE476.

The name **RoomMate** was selected to clearly reflect the system’s purpose (room booking), while remaining simple, memorable, and suitable for an open-source project. A brief check was also conducted to ensure the name does not conflict with widely known existing projects.

---

## Why This Project Is Free

RoomMate is released under the **MIT License**, allowing users to freely use, modify, and distribute the software. The only requirement is to include the original copyright notice.  
For full details, see the [`LICENSE`](LICENSE) file.

---

## Similar Projects

Before starting the project, a review of existing solutions was conducted:

| Project | Description | Link |
|---------|-------------|------|
| HotelDruid | Open-source hotel management system (PHP) | https://www.hoteldruid.com |
| OpenHotel | Property management system for small hotels | https://sourceforge.net/projects/openhotel |
| Roomify | Room booking system for Drupal | https://github.com/Roomify/roomify |

RoomMate differs by focusing on simplicity, educational use, and implementation using Java-based technologies.

---

## Features

- User registration with input validation  
- Room search and availability display  
- Reservation handling with conflict detection  
- Console-based interface (GUI planned for future phases)  
- JUnit 5 test suite for core functionality  
- Continuous Integration using GitHub Actions  

---

## The System (ITSE305 Project)

The core reservation system was developed in ITSE305. The source code, tests, and CI/CD pipeline are available in the following repository:

**→ [HotelReservationSystem Repository](https://github.com/BatoolAlsayed1/HotelReservationSystem)**

The system is implemented using Java 17, JUnit 5, and GitHub Actions.

---

## Development Status

**Phase 1 — In Progress**

The current focus is on preparing the open-source environment, including documentation, project structure, and contribution guidelines.

| Component | Status |
|-----------|--------|
| Core reservation system | Completed (ITSE305) |
| JUnit test suite | Completed |
| CI/CD pipeline | Active |
| Project website | In Progress |
| GitHub Pages hosting | Pending |
| Developer documentation | In Progress |

---

## Project Structure

```
ITSE476_project/
├── README.md
├── LICENSE
├── .gitignore
├── assets/                  # Images and static files
├── backend/                 # Backend logic (planned)
├── docs/
│   ├── CONTRIBUTING.md      # Contribution guidelines
│   └── FAQ.md               # Frequently asked questions
└── frontend/
    ├── index.html           # Main page
    ├── users/               # User pages and resources
    └── developers/          # Developer-related pages
```

---

## Team

| Name | Student ID | Responsibility |
|------|-----------|----------------|
| Bushra Hussain Habib | 202207555 | Main page, project overview, README, LICENSE |
| Esha | — | Users page, application resources |
| Zainab Abdiljuleel Mohammed | 202206573 | Contributors page, contribution guidelines |
| Fatima Sayed Saeed Yusuf | 202208285 | GitHub repository management, Wiki, project board |

---

## Contributing

Contributions are welcome. Please refer to [`docs/CONTRIBUTING.md`](docs/CONTRIBUTING.md) for guidelines on contributing, including branching, commit messages, and pull request procedures.

---

## License

This project is licensed under the MIT License. See [`LICENSE`](LICENSE) for details.

---

## Links

- Website: https://fatimaxYusuf.github.io/ITSE476_project  
- Bug Tracker: https://github.com/FatimaxYusuf/ITSE476_project/issues  
- Discussions: https://github.com/FatimaxYusuf/ITSE476_project/discussions  
- Wiki: https://github.com/FatimaxYusuf/ITSE476_project/wiki  
- Source Code: https://github.com/BatoolAlsayed1/HotelReservationSystem