# 🚀 Low-Level Design (LLD) & Machine Coding Repository

## 🎯 Overview

This repository contains a curated collection of **Low-Level Design (LLD) problems** frequently asked in technical interviews and machine coding rounds. Each problem is accompanied by:

- **Well-structured code implementations** ✅
- **UML/Draw.io diagrams for better understanding** 🎨
- **Best practices & explanations** 📘

Whether you are preparing for **FAANG interviews** or looking to enhance your **system design skills**, this repo is your go-to resource! 🚀

---

## 📌 Table of Contents

### 1️⃣ Object-Oriented Design (OOD)
- [Design a Parking Lot](https://github.com/SatyamRaj1905/Low-Level-Design/tree/main/1.ParkingLot)
- [Design an Elevator System](https://github.com/SatyamRaj1905/Low-Level-Design/tree/main/2.elevatorSystem)
- [Design a Car Rental System](https://github.com/SatyamRaj1905/Low-Level-Design/tree/main/3.CarRentalSystem)
- [Design a Meeting Scheduler](https://github.com/SatyamRaj1905/Low-Level-Design/tree/main/4.meetingScheduler)
- [Design a Vending Machine System](https://github.com/SatyamRaj1905/Low-Level-Design/tree/main/5.VendingMachineSystem)
- [Design LinkedIn (UCD)](https://github.com/SatyamRaj1905/Low-Level-Design/tree/main/6_1.LinkedIn-ucd.drawio)
- [LinkedIn Design (All Class Data)](https://github.com/SatyamRaj1905/Low-Level-Design/tree/main/6_2.LinkedIn-Design%20%5BAll%20Class%20Data%5D)
- [Design a Chess Game System](https://github.com/SatyamRaj1905/Low-Level-Design/tree/main/7.ChessGameSystem)
- [Design a Restaurant System](https://github.com/SatyamRaj1905/Low-Level-Design/tree/main/8.restaurantSystem)

### 2️⃣ System Requirements & Diagrams
- [ATM System Requirements](./ATM%20System%20Requirements.png)
- [Hotel Management System Requirements](./Hotel%20Management%20System%20Requirements.png)
- [Library System Requirements](./Library%20System%20Requirements.png)
- [Stack Overflow Requirements](./Stack%20Overflow%20Requirements.png)

---

## 📂 Directory Structure
Directory structure:
└── satyamraj1905-low-level-design/
    ├── README.md
    ├── 1.ParkingLot/
    │   ├── ParkingLot/
    │   │   ├── ParkingLot.iml
    │   │   ├── .gitignore
    │   │   ├── src/
    │   │   │   ├── Main.java
    │   │   │   ├── Interface/
    │   │   │   │   ├── Account.java
    │   │   │   │   ├── ParkingSpot.java
    │   │   │   │   ├── Payment.java
    │   │   │   │   └── Vehicle.java
    │   │   │   ├── constants/
    │   │   │   │   ├── AccountStatus.java
    │   │   │   │   └── PaymentStatus.java
    │   │   │   └── models/
    │   │   │       ├── AdminAccount.java
    │   │   │       ├── AgentAccount.java
    │   │   │       ├── Car.java
    │   │   │       ├── CardPayment.java
    │   │   │       ├── CashPayment.java
    │   │   │       ├── Compact.java
    │   │   │       ├── DisplayBoard.java
    │   │   │       ├── Entrance.java
    │   │   │       ├── Exit.java
    │   │   │       ├── Handicapped.java
    │   │   │       ├── Large.java
    │   │   │       ├── MotorCycle.java
    │   │   │       ├── MotorCycleVehicle.java
    │   │   │       ├── ParkingLotSystem.java
    │   │   │       ├── ParkingRate.java
    │   │   │       ├── ParkingTicket.java
    │   │   │       ├── Person.java
    │   │   │       ├── Truck.java
    │   │   │       └── Van.java
    │   │   └── .idea/
    │   │       ├── misc.xml
    │   │       ├── modules.xml
    │   │       ├── uiDesigner.xml
    │   │       └── .gitignore
    │   └── __MACOSX/
    │       └── ParkingLot/
    │           ├── ._.DS_Store
    │           └── src/
    │               └── ._.DS_Store
    ├── 2.elevatorSystem/
    │   ├── elevatorSystem.iml
    │   ├── .gitignore
    │   ├── src/
    │   │   ├── Main.java
    │   │   ├── constants/
    │   │   │   ├── DirectionStatus.java
    │   │   │   ├── DoorStatus.java
    │   │   │   └── ElevatorStatus.java
    │   │   └── models/
    │   │       ├── Building.java
    │   │       ├── Button.java
    │   │       ├── Display.java
    │   │       ├── Door.java
    │   │       ├── Elevator.java
    │   │       ├── ElevatorButton.java
    │   │       ├── ElevatorPanel.java
    │   │       ├── ElevatorSystem.java
    │   │       ├── Floor.java
    │   │       ├── HallButton.java
    │   │       └── HallPanel.java
    │   └── .idea/
    │       ├── misc.xml
    │       ├── modules.xml
    │       └── .gitignore
    ├── 3.CarRentalSystem/
    │   ├── CarRentalUseCase.drawio
    │   ├── CarRentalSystem/
    │   │   ├── CarRentalSystemClassDiagram.drawio
    │   │   ├── CarRentalSystemPriceDecorator.drawio
    │   │   ├── CarRentalUseCase.drawio
    │   │   ├── .$CarRentalSystemClassDiagram.drawio.bkp
    │   │   ├── .$CarRentalSystemPriceDecorator.drawio.bkp
    │   │   ├── .$CarRentalUseCase.drawio.bkp
    │   │   ├── .DS_Store
    │   │   └── CarRentalCode/
    │   │       ├── account.h
    │   │       ├── basicheader.h
    │   │       ├── branch.h
    │   │       ├── datatypes.h
    │   │       ├── enums.h
    │   │       ├── equipment.h
    │   │       ├── fine.h
    │   │       ├── main.cpp
    │   │       ├── notification.h
    │   │       ├── parkingstall.h
    │   │       ├── payment.h
    │   │       ├── rentalsystem.h
    │   │       ├── search.h
    │   │       ├── service.h
    │   │       ├── vehicle.h
    │   │       ├── vehicledecorators.h
    │   │       ├── vehiclelog.h
    │   │       └── .vscode/
    │   │           └── settings.json
    │   └── __MACOSX/
    │       ├── ._CarRentalSystem
    │       └── CarRentalSystem/
    │           ├── ._.$CarRentalSystemClassDiagram.drawio.bkp
    │           ├── ._.$CarRentalSystemPriceDecorator.drawio.bkp
    │           ├── ._.$CarRentalUseCase.drawio.bkp
    │           ├── ._.DS_Store
    │           ├── ._CarRentalCode
    │           ├── ._CarRentalSystemClassDiagram.drawio
    │           ├── ._CarRentalSystemPriceDecorator.drawio
    │           ├── ._CarRentalUseCase.drawio
    │           └── CarRentalCode/
    │               ├── ._.vscode
    │               ├── ._account.h
    │               ├── ._basicheader.h
    │               ├── ._branch.h
    │               ├── ._datatypes.h
    │               ├── ._enums.h
    │               ├── ._equipment.h
    │               ├── ._fine.h
    │               ├── ._main.cpp
    │               ├── ._notification.h
    │               ├── ._parkingstall.h
    │               ├── ._payment.h
    │               ├── ._rentalsystem.h
    │               ├── ._search.h
    │               ├── ._service.h
    │               ├── ._vehicle.h
    │               ├── ._vehiclelog.h
    │               └── .vscode/
    │                   └── ._settings.json
    ├── 4.meetingScheduler/
    │   └── meetingScheduler/
    │       ├── meetingScheduler.iml
    │       ├── .gitignore
    │       ├── src/
    │       │   ├── Main.java
    │       │   └── models/
    │       │       ├── Calendar.java
    │       │       ├── Interval.java
    │       │       ├── Meeting.java
    │       │       ├── MeetingRoom.java
    │       │       ├── MeetingScheduler.java
    │       │       ├── MeetingSchedulingSystem.java
    │       │       ├── Notification.java
    │       │       └── User.java
    │       └── .idea/
    │           ├── misc.xml
    │           ├── modules.xml
    │           └── .gitignore
    ├── 5.VendingMachineSystem/
    │   ├── VendingMachineSystem.iml
    │   ├── .gitignore
    │   ├── src/
    │   │   ├── Main.java
    │   │   ├── Models/
    │   │   │   ├── Admin.java
    │   │   │   ├── DispenseProductState.java
    │   │   │   ├── IState.java
    │   │   │   ├── MoneyInsertedState.java
    │   │   │   ├── NoMoneyInsertedState.java
    │   │   │   ├── Notification.java
    │   │   │   ├── Product.java
    │   │   │   ├── Rack.java
    │   │   │   ├── Slot.java
    │   │   │   └── VendingMachine.java
    │   │   └── constants/
    │   │       ├── NotificationType.java
    │   │       └── ProductType.java
    │   └── .idea/
    │       ├── misc.xml
    │       ├── modules.xml
    │       ├── uiDesigner.xml
    │       └── .gitignore
    ├── 6_1.LinkedIn-ucd.drawio/
    │   └── LinkedIn-ucd.drawio
    ├── 6_2.LinkedIn-Design [All Class Data]/
    │   ├── LinkedIn-Design [All Class Data]/
    │   │   ├── LinkedIn-ClassDiagram.drawio
    │   │   ├── LinkedIn-ucd.drawio
    │   │   ├── .DS_Store
    │   │   └── LinkedIn-code/
    │   │       ├── account.h
    │   │       ├── achievement.h
    │   │       ├── analytics.h
    │   │       ├── observer.h
    │   │       ├── persona.h
    │   │       ├── professionalComponents.h
    │   │       ├── profile.h
    │   │       ├── recommendation.h
    │   │       ├── searchCatalogNotification.h
    │   │       ├── socialInteraction.h
    │   │       ├── subject.h
    │   │       ├── utils.h
    │   │       └── .DS_Store
    │   └── __MACOSX/
    │       └── LinkedIn-Design [All Class Data]/
    │           ├── ._.DS_Store
    │           └── LinkedIn-code/
    │               └── ._.DS_Store
    ├── 7.ChessGameSystem/
    │   ├── ChessGameSystem.iml
    │   ├── .gitignore
    │   ├── src/
    │   │   ├── Main.java
    │   │   ├── constants/
    │   │   │   ├── AccountStatus.java
    │   │   │   └── GameStatus.java
    │   │   └── models/
    │   │       ├── Account.java
    │   │       ├── Admin.java
    │   │       ├── Bishop.java
    │   │       ├── Box.java
    │   │       ├── ChessBoard.java
    │   │       ├── ChessCommand.java
    │   │       ├── ChessGameSystem.java
    │   │       ├── ChessGameView.java
    │   │       ├── King.java
    │   │       ├── Knight.java
    │   │       ├── Move.java
    │   │       ├── Pawn.java
    │   │       ├── Person.java
    │   │       ├── Piece.java
    │   │       ├── Player.java
    │   │       ├── Queen.java
    │   │       └── Rook.java
    │   └── .idea/
    │       ├── misc.xml
    │       ├── modules.xml
    │       └── .gitignore
    └── 8.restaurantSystem/
        ├── restaurantSystem.iml
        ├── .gitignore
        ├── src/
        │   ├── Main.java
        │   ├── constants/
        │   │   ├── AccountStatus.java
        │   │   ├── OrderStatus.java
        │   │   ├── PaymentStatus.java
        │   │   ├── ReservationStatus.java
        │   │   ├── SeatType.java
        │   │   └── TableStatus.java
        │   └── models/
        │       ├── Account.java
        │       ├── Bill.java
        │       ├── Branch.java
        │       ├── Card.java
        │       ├── Cash.java
        │       ├── Check.java
        │       ├── Chef.java
        │       ├── Customer.java
        │       ├── Employee.java
        │       ├── Kitchen.java
        │       ├── Manager.java
        │       ├── Meal.java
        │       ├── MealItem.java
        │       ├── Menu.java
        │       ├── MenuItem.java
        │       ├── MenuSection.java
        │       ├── Notification.java
        │       ├── Order.java
        │       ├── Payment.java
        │       ├── Person.java
        │       ├── Receptionist.java
        │       ├── Reservation.java
        │       ├── Restaurant.java
        │       ├── RestaurantSystem.java
        │       ├── Table.java
        │       ├── TableChart.java
        │       ├── TableSeat.java
        │       ├── Waiter.java
        │       ├── command/
        │       │   ├── AddEntryCommand.java
        │       │   ├── Command.java
        │       │   ├── CommandInvoker.java
        │       │   ├── Database.java
        │       │   ├── DeleteEntryCommand.java
        │       │   ├── Entry.java
        │       │   └── ModifyEntryCommand.java
        │       ├── factory/
        │       │   ├── MenuItemFactory.java
        │       │   └── MenuManagement.java
        │       └── observer/
        │           ├── Observer.java
        │           └── Subject.java
        └── .idea/
            ├── misc.xml
            ├── modules.xml
            ├── uiDesigner.xml
            └── .gitignore


## 📜 How to Use

1. **Clone the repository**
   ```sh
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
   ```
2. **Navigate through different design problems**  
   Each problem has a **detailed markdown file** and corresponding **code implementation**.
3. **Refer to the Draw.io diagrams** for better visualization.

---

## 🤝 Contributing

Contributions are **welcome**! Feel free to submit:
- New problems & solutions 📂
- Improvements in explanations 📝
- Better diagrams 🎨
- Optimized code implementations ⚡

### Steps to Contribute:
1. Fork the repo 🍴
2. Create a new branch `feature/your-feature-name` 🌿
3. Commit changes & push 🚀
4. Create a PR with a proper description 🔥

---

## 📢 Community & Support

For discussions, feedback, or queries, feel free to **open an issue** or reach out via **LinkedIn/Twitter**.

If you find this repo helpful, don't forget to **⭐ Star** it! Happy Coding! 😊🚀

