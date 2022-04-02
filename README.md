# Avoid_Making_Jenkins_Common_Mistakes

However, this raises another question: “What if I do not have any agents 
connected to my controller?” 

If this is the case, then you have just made another  bad mistake in scaling Jenkins pipelines. 

Why? Because the first rule of building an effective pipeline is to make sure you use agents. 

If you are using a Jenkins controller and have not defined any agents, then your first step should be to define at least one agent and use that 
agent instead of executing on the controller. 

For the sake of maintaining scalability in your pipeline, the general rule is to 
avoid processing any workload on your controller.
