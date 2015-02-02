# Autoverleih

Dies ist ein Semester-Projekt im Kurs "Software Architektur & Design".


## 1. C4 Modell

### 1.1 Context

### 1.2 Containers
Three Thier:
- Application Server
- Database Server
- CLient(s)

#### 1.2.1 Application Server
Enthält die Business-Logik. Kommuniziert über einen Query-Stream mit dem Database Server.

#### 1.2.2 Database Server
Datenhaltung.

#### 1.2.3 Client
WEB CLient etc. Kommuniziert über HTTP (REST) mit dem Application Server.

### 1.3 Components
- Service (Kommunikation zwischen Client & Application Server)
- Foundation & Domain (Kommunikation zwischen Application Server & Database Server: REST, Netzwerkkommunikation etc.)
- Kundenverwaltung (customers)
- Reservationssystem (reservations)
- Autoverwaltung (cars)

### 1.4 Classes
