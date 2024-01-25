---
banner: "![[furthermaths.jpg]]"
---
# Early and Late Event Times

> [!Info] Activitiy times
> - Activities within a project typically take different lengths of time to complete
> - The early event time is the *earliest* time of arrival at the event, allowing for the completion of all preceding activities.
> - The late event time is the latest time that the event can be left without extending the time needed for the project.
> 
> - The early event times are calculated starting from 0 at the source node and working towards the sink node. (forward scan/pass)
> - The late event times are calculated starting from the sink node and working backwards towards the source node. (backward scan/pass)
> 
> - If there is no float for an activity then it is considered a *critical activity*.
> 
> ![[maxresdefault.jpg|500]]

> [!Info] The forward pass
> - On the forward pass, we take the maximum value possible of the arcs going into the target node.

> [!Info] The backwards pass
> - On the backwards pass, we take the minimum possible value of the arcs going into the target node.
