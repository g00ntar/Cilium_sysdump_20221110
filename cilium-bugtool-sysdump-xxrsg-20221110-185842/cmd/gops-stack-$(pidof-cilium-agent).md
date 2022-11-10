gops: Missing PID or address.
gops is a tool to list and diagnose Go processes.

Usage:
  gops <cmd> <pid|addr> ...
  gops <pid> # displays process info
  gops help  # displays this help message

Commands:
  stack      Prints the stack trace.
  gc         Runs the garbage collector and blocks until successful.
  setgc	     Sets the garbage collection target percentage.
  memstats   Prints the allocation and garbage collection stats.
  version    Prints the Go version used to build the program.
  stats      Prints runtime stats.
  trace      Runs the runtime tracer for 5 secs and launches "go tool trace".
  pprof-heap Reads the heap profile and launches "go tool pprof".
  pprof-cpu  Reads the CPU profile and launches "go tool pprof".

All commands require the agent running on the Go process.
"*" indicates the process is running the agent.
> Error while running 'gops stack $(pidof cilium-agent)':  exit status 1

