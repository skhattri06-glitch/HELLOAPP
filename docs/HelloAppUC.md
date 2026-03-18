# HelloApp Use Cases

## UC1: Print a Basic Greeting

**Goal:** Print "Hello World" to the console.

**Implementation:**
- Create a `HelloApp` class with a `main` method
- Use `System.out.println()` to display the message

**Expected Output:**
```
Hello World
```

---

## UC2: Accept One Name via Command-Line Input

**Goal:** Greet a user by name passed as a command-line argument.

**Expected Output:**
```
Hello <name>
```

---

## UC3: Support Optional Argument Handling

**Goal:** If no name is provided, fall back to a default greeting.

---

## UC4: Handle Multiple Command-Line Names

**Goal:** Accept and greet multiple names provided as command-line arguments.

---

## UC5: Read a Single Name from Standard Input

**Goal:** Prompt the user to enter their name and greet them.

---

## UC6: Read and Process Multiple Names from Standard Input

**Goal:** Allow multiple names to be entered and greet each one.

---

## UC7: Store Entered Names in Memory

**Goal:** Maintain a list of names in memory; support listing all stored names.

---

## UC8: Add Removal Support for Stored Names

**Goal:** Allow a specific name to be removed from the stored list.

---

## UC9: Extract Input-Processing Logic into Methods

**Goal:** Refactor the code to separate concerns into dedicated methods.

---

## UC10: Move Name-Management into a Separate Class

**Goal:** Create a dedicated class to manage the name collection.

---

## UC11: Persist Names Across Runs

**Goal:** Save names to a file and reload them on the next run.

---

## UC12: Display Names in Banner Format

**Goal:** Render greeting text using banner-style ASCII output.
