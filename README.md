# jetbrains-cleanupcode-perf-issues

Command to run for each version:
```sh
dotnet tool restore --verbosity minimal
dotnet jb cleanupcode --verbosity=WARN --include="$PWD/Class.cs"
```

Execution of cleanup of a plain Class.cs file on v2022.3.3.

![image](https://github.com/user-attachments/assets/e8bd4aed-2452-4011-951e-43232dbd92d5)

Execution of cleanup of a plain Class.cs file on v2024.2.5.
![image](https://github.com/user-attachments/assets/c79b32f4-4a64-42a0-a97f-cbfec5079089)
