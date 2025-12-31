Ai Agent
1 . When to use tool 
2. which tools to use 
3. what input arguments are 
4. how to pass input arguments
5. how to parse and interpret results

too many tools and too less tools
explictly instructions when and how to use tools 

context engineering - clear and concise descriptions of what each tool does.

Tool
    id
    description
    input schema
    output schema
    execution logic

Native tools vs MCP server tools
Native tools - attach to agent at time of initialization (via function call) - tightly coupled to core codebase
MCP tools discovery is dynamic  - external services for docs , data and SaaS - discoveable and updatable through configuration without touching deployment
