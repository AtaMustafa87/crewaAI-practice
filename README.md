# crewaAI-practice
Crew AI Projects

# Flows
* Flows allow you to create structured, event-driven workflows:
  1. Simplified workflow creation
  2.  State Management
  3. Event-Driven Architecture
  4. Flexible Control Flow
* Each flow has unique, the ID is assigned at the time of flow creation. _start_ and _listen_ are key methods
* Structured as well as unstructured state management using _state_ variable in the class, the final value is retrieved using final method output
* Persistance can be achieved at function as well as class level
* Flow control using _or__, _and__, and _router_
* To add crew to flow _crewai create flow name_of_flow_
* You may plot flows using _flow.plot_ function or using _crewai flow plot_
  
# Crew
A crew in crewAI represents a collaborative group of agents working together to achieve a set of tasks. Each crew defines the strategy for task execution, agent collaboration, and the overall workflow.
* Create crew using YAML file or using code
* Output of crew is encapsulated in _CrewOutput_, it can be retrieved in the form of raw string, dictionary or json
* Memory utilization, Cache Utilization, Crew Usage metrics
* Crew execution processes, Sequential and Hierarchical
* Different ways to kickoff crew, simple kickoff, kickoff_for_each, kickoff_async, and kickoff_for_each_async.
* Replaying a specific task using cli _crewai log-tasks-outputs_ then _crewai replay -t <task_id>_

# Agent
* An agent:
  * Perform specific tasks
  * Make decisions based on its role and goal
  * Use tools to accomplish objectives
  * Communicate and collaborate with other agents
  * Maintain memory of interactions
  * Delegate tasks when allowed

# Task
In the CrewAI framework, a Task is a specific assignment completed by an Agent.

Tasks provide all necessary details for execution, such as a description, the agent responsible, required tools, and more, facilitating a wide range of action complexities.

Tasks within CrewAI can be collaborative, requiring multiple agents to work together. This is managed through the task properties and orchestrated by the Crew’s process, enhancing teamwork and efficiency.

* Like Crew, there are two ways to create agent using YAML or using code
* Agent tools, CrewAI toolkit and LangChain toolkit
* Agent can have memory and context stored for later use

* 
