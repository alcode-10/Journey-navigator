# Journey-navigator
**Journey Navigator** is a C++ console-based application that helps users find the shortest travel route, optimize journey plans based on time or cost, and generate Huffman-coded ticket IDs. It features user authentication, route planning using Dijkstra’s algorithm, and a feedback system, making travel planning efficient and interactive. 🚀

Here’s a README file description for your GitHub repository:

---

## Journey Navigator

### Short Description:
Journey Navigator is a C++ console-based application that helps users find the shortest path between cities, plan their journeys efficiently based on time or cost, and generate travel tickets with unique Huffman-coded IDs. It includes user authentication, feedback collection, and an intuitive interface for route planning.

### Features:
- **User Authentication:** Sign up and log in to manage travel plans.
- **Shortest Path Calculation:** Uses Dijkstra's algorithm to find the optimal route.
- **Travel Mode Optimization:** Suggests the best travel mode (Flight, Train, Cab) based on time or cost.
- **Huffman-coded Ticket Generation:** Generates unique ticket IDs using Huffman coding.
- **Feedback System:** Allows users to rate their experience.
- **File-Based Data Handling:** Stores user credentials and city information in files.

### Technologies Used:
- **C++**
- **Data Structures (Graphs, Priority Queues)**
- **File Handling**
- **Algorithms (Dijkstra's Algorithm, Huffman Coding)**

### How to Use:
1. **Compile the Program:**  
   ```bash
   g++ mainf.cpp -o journey_navigator
   ```
2. **Run the Program:**  
   ```bash
   ./journey_navigator
   ```
3. **Choose an option:**  
   - Log in or sign up.  
   - Find the shortest path.  
   - Select cost-effective or time-effective journey plans.  
   - Generate a travel ticket.  
   - Provide feedback.

 Future Enhancements:
- **Graphical User Interface (GUI)**
- **Integration with Real-World Travel APIs**
- **More Transport Options and Dynamic Pricing**

