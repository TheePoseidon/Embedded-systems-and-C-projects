# C Programming Summative


### **1. Smart Traffic Light System**

**Link:** [Tinkercad Project](https://www.tinkercad.com/things/1AH80oNS9lr-smart-traffic-control-and-monitoring-system?sharecode=--uqGRiU2WtpkinETE4Y_ZYKsL66Y_xyJLF4Qs298_I)
**Path:** `Project_1_Traffic_Light/traffic_light.ino`

A simplified embedded traffic light system implemented using Arduino.

**Features:**

* Non-blocking timing using `millis()`
* Dynamic green time based on vehicle queue
* Simple hardware: 3 LEDs + 1 button
* Debug output via Serial
* Fully compatible with Tinkercad Circuits

**Run:**
Import the `.ino` file into Arduino IDE or Tinkercad and upload to your board.

---

### **2. Advanced System Monitoring Script**

**Path:** `Project_2_System_Monitor/monitor.sh`

A Bash-based system utility to monitor CPU, RAM, and disk usage.

**Features:**

* No root access required
* Logs saved under `~/sysmonitor.log`
* Threshold-based alerts
* Menu-driven interface
* Background monitoring mode

**Run:**

```bash
chmod +x monitor.sh
./monitor.sh
```

---

### **3. Student Management System**

**Path:** `Project_3_Student_Management/student_management.c`

A C program for managing student records with analytics and persistent storage.

**Features:**

* Create, read, update, delete student entries
* Data stored in binary format
* Sorting by GPA, name, or ID using `qsort`
* Reporting: averages, top students, distributions
* Robust input validation and error handling

**Compile & Run:**

```bash
gcc student_management.c -o student
./student
```

---

### **4. Dynamic Math & Data Processing Engine**

**Path:** `Project_4_Math_Engine/math_engine.c`

A modular and extensible computational engine.

**Features:**

* Function pointers for dynamic operation selection
* Dynamic memory allocation for datasets
* File-based dataset loading and saving
* Searching, sorting, statistical operations
* Clean terminal UI

**Compile & Run:**

```bash
gcc math_engine.c -o mathengine
./mathengine
```

---

### **5. Multi-threaded Web Scraper**

**Path:** `Project_5_Web_Scraper/scraper.c`

A POSIX-thread-based web scraping simulator.

**Features:**

* Parallel page fetching
* Thread-isolated file outputs
* Simulated URLs (no external dependencies)
* Graceful error handling for invalid URLs
* Proper thread lifecycle management

**Compile & Run:**

```bash
gcc scraper.c -o scraper -lpthread
./scraper
```

---

## **Technologies Demonstrated**

* Low-level C programming: pointers, structs, dynamic memory
* File I/O (binary and text)
* Algorithm design: sorting, searching, reporting
* Bash scripting and Linux utilities
* Multi-threading with POSIX pthreads
* Modular design and code documentation

---

## **Repository Structure**

```
Project_1_Traffic_Light/
Project_2_System_Monitor/
Project_3_Student_Management/
Project_4_Math_Engine/
Project_5_Web_Scraper/
README.md
```

---
