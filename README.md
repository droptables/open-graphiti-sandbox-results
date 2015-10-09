These data sets are to be used with opengraphiti.com for 3D visualization.


Each file is the result of detonating a piece of malware within a sandbox and recording the following activity:

- Modules Loaded: Various, exes, DLLs, etc. loaded at run time
- Registry Actions: Create, Write, Delete
- File Actions: Creates, Writes, Deletes
- Network Connections: Domains contacted

These data points are plotted along a circuit of Time Nodes (Down to the second, 14:04:25->14:04:26->14:04:27)

Studying program activity and malware on this level with OpenGraphiti yields a lof of interesting discoveries and new ways to study the 'Molecular Makeup' of process executions when something runs on an endpoint.

I will be giving a talk on this research October 2015 and will continue to share the research and open sourcing the project of converting sandbox activity to an OpenGraphiti format.

Big thanks to the team that made OpenGraphiti open source :)