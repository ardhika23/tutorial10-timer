# 📝Tutorial & Exercise 10📝

**Student Details :**

|  Attribute    | Information                |
|---------------|----------------------------|
| Name          | Ardhika Satria Narendra    |
| Student ID    | 2206821866                 |
| Class         | Advanced Programming KKI   |

---
<details>
<summary>Module 10: High Level Networking</summary>

## Questions and Answers

### -> Reflection 

#### 1.2: Understanding how it works

When I spawn a task using the provided spawner, it initiates an asynchronous process. The task is programmed to print "Ardhika's Computer: howdy!" and then waits for 2 seconds before printing "Ardhika's Computer: done!". In this experiment, I have inserted a synchronous println!("Ardhika's Computer: hey hey"); statement right before the asynchronous spawner call in the main function.

As a result, when the program runs, the synchronous println! statement executes immediately, outputting "Ardhika's Computer: hey hey" directly to the console. This is because synchronous code executes in the order it is written and completes before moving on. On the other hand, the asynchronous task that was spawned right after waits for its turn on the executor to start its execution. Once it begins, there is a 2-second pause implemented in the code, following which it prints "Ardhika's Computer: howdy!" and after another 2 seconds, concludes with "Ardhika's Computer: done!".

---

</details>