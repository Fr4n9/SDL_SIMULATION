# SDL_SIMULATION_COFFEE

Project developed during the 6th trimester for the Simulation (SIM) subject ([Course Info](https://www.fib.upc.edu/en/studies/bachelors-degrees/bachelor-degree-informatics-engineering/curriculum/syllabus/SIM)) at the FIB, Universitat Politècnica de Catalunya in Barcelona.  
It is a **G/G/C simulation model** implemented in **SDL**, where:
- The arrival and service times follow **general distributions**.
- The number of servers (**C**) is configurable and greater than 0.

In this specific project:
- We simulate a queueing system with **2 types of servers**:
  - **1 fixed coffee machine**.
  - **C snack servers**, where **C ≥ 1** and is configurable.

The simulation models how students queue to get snacks or coffee, using the techniques and concepts learned in the final chapter of the course.

### Developed by:
- Adrián Ferrer  
- Francesc Pérez

---

## Project Characteristics

- **100 students** arrive to the machine area over a span of time, with **inter-arrival times of 9 minutes ± 3 minutes (variance)**.
- Each student has:
  - **40% probability** of choosing the **snack** queue.
  - **60% probability** of choosing the **coffee** queue.
- The system has:
  - **1 coffee machine** (fixed).
  - **C snack servers**, where C is a configurable integer > 0.
- **Queues manage the customer flow**: they send users to available servers and wait for a response before dispatching the next user.
- A **state diagram** has been created to illustrate how the system reacts to inputs and communicates with other processes.

---

## How to Open the Project

The project has been created using **draw.io (diagrams.net)**.

You can view and edit it directly using the following link:

👉 [Open GGC SDL Simulation Diagram (View & Edit)](https://is.gd/g0BDUl)

- You can **view the diagram** directly in your browser.
- If you click the **pencil icon**, you can also **edit** it in draw.io.
- Alternatively, you can scroll down to see **screenshots of the diagrams** already included in this README for a quick overview.

> No additional installation is required — everything works online.


---

## System Diagram images

![alt text](https://github.com/Fr4n9/SDL_SIMULATION/blob/main/GGC_Francesc_Adrian_SDL_SImulation-GGC%20system.drawio.png)

## Block Diagram images

![alt text](https://github.com/Fr4n9/SDL_SIMULATION/blob/main/GGC_Francesc_Adrian_SDL_SImulation-BGenerator.drawio.png)
![alt text](https://github.com/Fr4n9/SDL_SIMULATION/blob/main/GGC_Francesc_Adrian_SDL_SImulation-BQueueCoffee.drawio.png)
![alt text](https://github.com/Fr4n9/SDL_SIMULATION/blob/main/GGC_Francesc_Adrian_SDL_SImulation-BQueueSnack.drawio.png)
![alt text](https://github.com/Fr4n9/SDL_SIMULATION/blob/main/GGC_Francesc_Adrian_SDL_SImulation-BServerCoffee.drawio.png)
![alt text](https://github.com/Fr4n9/SDL_SIMULATION/blob/main/GGC_Francesc_Adrian_SDL_SImulation-BServerSnack.drawio.png)


## States Diagram image

![alt text](https://github.com/Fr4n9/SDL_SIMULATION/blob/main/GGC_Francesc_Adrian_SDL_SImulation-States%20Diagrams.drawio.png)

## Process Diagram images

![alt text](https://github.com/Fr4n9/SDL_SIMULATION/blob/main/GGC_Francesc_Adrian_SDL_SImulation-PGenerator.drawio.png)
![alt text](https://github.com/Fr4n9/SDL_SIMULATION/blob/main/GGC_Francesc_Adrian_SDL_SImulation-PQueueCoffee%20-%20EMPTY.drawio.png)
![alt text](https://github.com/Fr4n9/SDL_SIMULATION/blob/main/GGC_Francesc_Adrian_SDL_SImulation-PQueueCoffee%20-%20NOEMPTY.drawio.png)
![alt text](https://github.com/Fr4n9/SDL_SIMULATION/blob/main/GGC_Francesc_Adrian_SDL_SImulation-PQueueSnack%20-%20EMPTY.drawio.png)
![alt text](https://github.com/Fr4n9/SDL_SIMULATION/blob/main/GGC_Francesc_Adrian_SDL_SImulation-PQueueSnack%20-%20NOEMPTY.drawio.png)
![alt text](https://github.com/Fr4n9/SDL_SIMULATION/blob/main/GGC_Francesc_Adrian_SDL_SImulation-PServerCoffee.drawio.png)
![alt text](https://github.com/Fr4n9/SDL_SIMULATION/blob/main/GGC_Francesc_Adrian_SDL_SImulation-PServerSnack.drawio.png)





