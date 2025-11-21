# 🖥️ OS Lab Assignment 1 — Process Creation and Management Using Python



# 📌 Overview

In this assignment, students will simulate Linux process management operations using Python. The experiment focuses on replicating the behaviors of fork(), exec(), and process state inspections using the os and subprocess modules in Python. It provides an understanding of process creation, child-parent relationship, and zombie/orphan process scenarios.


# 🚀 Experiments

Process Creation Utility — Create multiple child processes using os.fork() and synchronize with os.wait().

Command Execution — Execute Linux commands via os.execvp() in child processes.

Zombie & Orphan Simulation — Demonstrate process states and parent-child dependencies.

/proc Inspection — Retrieve process details (PID, state, memory, etc.) from /proc/[pid]/status.

Process Prioritization — Observe scheduling effects using different nice values.

# ⚙️ Complexity

Time Complexity: O(n)

Space Complexity: O(n)

#🧠 Key Learnings

Lifecycle and states of processes (creation → execution → termination).

Fork–exec mechanism in Linux.

Real-time process inspection using /proc.

Scheduler behavior under different priorities.

#📄 Conclusion

The experiment provided hands-on understanding of process creation, scheduling, and inspection, reinforcing OS concepts through Python simulations.
