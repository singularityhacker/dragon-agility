---

title: "Data Driven"  
date: 2021-04-13T15:15:26+10:00  
featured: true  
weight: 3  
layout: service

---

There's no shortage of people or systems claiming to have the right or best way to do things. And most of them have the white papers and research to back it up. So how does one navigate these competing and sometimes contradictory approaches? Even if you do move forward with a particular method of organization, how do you know if you've achieved the results you're supposed to or how do you know that you've implemented it properly and gotten the promised benefits? One problem with this is it frequently, peoples subjective feelings related to working hard and getting things done become the standard of success. This is highly problematic and I don't need to go to Great Lengths to prove that. With money, resources, end time on the line, we should not be relying on subjective impressions of improvement.

## Data Driven Goals and Results

One of the most prominent convictions and values of the Dragon agility group is 2 increase the rigor of agile methods. This means establishing Baseline metrics for a system before implementing changes such that the impact of those changes can be empirically and objectively measured after. Now exactly what those metrics are may change with time and with learning and as well what those practices are will change put the relationship in the priority of a measure-test-measure feedback loop should not change.

## Measuring Delivery with Agile Delivery Metrics

Agile delivery metrics have been treated like Alchemy for far too long. The confusion could not be deeper regarding what produces a predictable and stable software delivery system. In fact, it was the very concern in this area that prompted the birth of the Dragon Agility Group. We have gone to great lengths to cut through the FUD on this issue and produced a rigorous and comprehensive method for measuring and improving the rate and predictability of software delivery. We've even gone so far as to instantiate our methodology into a software tool called Animus BI. 

In contrast to the current landscape of consultants and a disparate hodgepodge of agile reporting metrics, we lay out a clear, succinct, and effective strategy for measuring and optimizing an agile program's delivery process. There are five main charts (a collection of associated metrics) that should drive its delivery process. Lets look at each in logical order.

The first point to be made before getting into the details is that these charts should be real-time and publicly visible. If they are not seen or can’t be used for self-correction then they won’t be effective tools for change. This means dashboards. They should display visual summaries of critical data points and include only what matters most. If there is a problem, it should be highlighted in such a way as to enable users to drill into the details to more closely examine issues.

**Cycle Time Scatterplot**

The first metric we’ll want to look at is the cycle time scatterplot chart. This chart shows the lifespan of completed issues. It charts, in days, how long it took an issue to be completed once it was started. So why does cycle time matter? It matters because, in a team’s workflow, cycle time is the irreducible unit of delivery. If an upper bound can be established for work items using average cycle times, your work items become predictable, as does your entire delivery process. The rule of thumb is that 95% (or better) of all work items should be completed in less time than the length of your iterations. If this is achieved, then teams will by definition consistently meet iteration goals. Another benefit of using the cycle time metric is — it is useful irrespective of team-given work item estimates. This means that cycle time allows a team to predict when work will be done before estimating individual work items.

The main weakness of the cycle time chart is that any issues that appear on it have already been completed and therefore can’t be influenced. That is to say; once a particular item has exceeded the maximum target cycle time, it is already too late to do anything about it. Considered in this way the cycle time scatter plot chart is a lagging indicator. If this is the case then what do we do to impact future work item cycle times? This takes us to our next chart.

**Work Item Age Chart**

The work item age chart shows all items that have started but have not been completed, what current state they are in, how old they are, and how at-risk they are of exceeding the maximum cycle time. This is extremely useful because a team can review this screen daily to coordinate necessary actions to address issues before they exceed targeted cycle times. This screen acts as the leading indicator and visual cue that, if monitored closely and used intentionally, is a powerful lever enabling teams to directly control their cycle times. If the cycle time metric represents a stable heartbeat then our next report we’re going to look at represents what a healthy volume of blood flow should look like.

**Cumulative Flow Diagram**

While the cycle time scatter-plot and the work item age chart work in tandem to ensure work is progressing and flowing in a predictable fashion, another chart is required to fully flesh out the health of a team’s workflow. This is because it would be possible to have short predictable cycle times and yet still have inefficient flow. The cumulative flow diagram (CFD) works to highlight those bottlenecks.

A healthy CFD will be represented by evenly spaced bands. If there’s a lump or a pinch in one of the bands, that means that work has piled up or been excessively depleted from that workflow. Even in a system where no individual items are exceeding cycle time targets, work entering or leaving the system at different rates signals potential problems in the future and opportunities for improved efficiency in individual workflow states.

Now that we’ve covered screens and metrics that measure the flow of a team’s work, let’s shift our attention to a team’s batch delivery. That is, how frequently, and at what schedule do they plan to integrate and release new versions of the product. This takes us to the next and last two charts.

**Iteration Burndown Chart**

A typical iteration report shows the work a team has committed to and the rate at which that work is completed over the course of that iteration. This sounds simple but there are a number of potential gotchas involved.

A big one is that when team members working in the first half of the workflow complete an item and pass it on to future work states, do they pick up additional work from the backlog and add it to the iteration? If the iteration board is supposed to capture all in-flight work and be a canonical source of what the team is working on, then you would argue that it should be added. But the problem with this is that if new work gets added to the iteration the report won’t display a real burndown. A continuous flow of work in combination with a standard iteration report will never produce a burndown. It can’t.

Some teams try to compensate for this by not pulling additional work into the iteration once it has started but this is a faulty way of working brought on by a deficiency in the report itself. Tools and reports should amplify and incentivize transparency, not the opposite.

There are various realities that should be taken into account as an iteration progresses and many reporting tools either ignore them or actively incentivize undesirable patterns. An iteration report should take into account at least the following four metrics in a clearly visible fashion.

1.  Elapsed Time
2.  Completed Story Points
3.  Completed Work Items
4.  Completed User Stories

By breaking things out in the way described above, we are able to distinguish the volume, value, and type of that work relative to time. Viewed in this way, we gain insight into the delivery of work along several axes. There is one last level of batch size, and that is at the level of the release.

**Release Report**

While the iteration is designed to produce a new, potentially shippable, version of the product, a release is a thematic collection of accumulated changes over the course of one or more iterations. Even though best practice demands that a new product increment be potentially shippable at the end of every iteration, most organizations batch the work of several iterations to be released in coordination with other parts of the business. Other factors like the time and cost of regression testing may affect how frequently organizations release as well. The release report chart is potentially the most comprehensive report of all the charts we have covered because it must take into account all the previous historical metrics we’ve covered to produce a reliable forecast.

**An Analogy**

This progression through each of the charts and metrics we have covered and can be illustrated with an analogy. Picture a conveyor belt continuously outputting widgets into the bed of a truck and once that truck is full, it drives away and loads its contents into a rocket. After several trips, the rocket is full and flies away to its destination and the process starts again. That conveyor belt is your workflow and its operation is optimized by the cycle time scatter plot and the work item age chart.

That pickup truck is your iteration. The goal is to fill it with the highest value items in a shippable unit such that any single load could be shipped in isolation and still provide real value. This is monitored and achieved leveraging the iteration report.

Lastly, we have the rocket ship which represents a release. A single truckload could be loaded to the rocket ship and it could take off but it’s more efficient to batch together several loads in a single celestial journey so this mirrors the typical pattern of batching together the results of several iterations enter a single release.

Everyone wants to be able to determine when releases will ship but it’s only by focusing first on the smallest unit of delivery (the flow of user stories) and then moving up through the succeeding layers using these tightly coupled metrics that we’re able to forecast with a real level of confidence.

## Measuring culture

What about the intangibles you ask. What about the human element? We are in fact dealing with people, not machines. Once again, this doesn't mean that we don't try to understand things in it structured in a measurable way. It's for this reason that we prescribe and practice regular pulse checks of individual and team satisfaction and subjective experience of work. We do this through surveys and interviews immediately following onboarding training, exit interviews, and regular pulse surveys. 

## Program Evaluation and Baselining 

We offer a program evaluation service that can get you started down this road of empirical evaluation and analysis. It involves the following:

1.  We start by establishing a basic model have your delivery system
2.  Second, we establish what metrics can be ascertained from the existing system
3.  Thirdly, using your model and available metrics we establish the best available Baseline for how effectively you currently operate
4.  Lastly, we provide a report suggesting changes to your model and available metrics that would produce a higher fidelity and more controllable system

Armed with the above leadership can then make more informed decisions on areas of growth are possible next steps. One could compare it to a physical examination prior to starting a new training routine. The results of the physical should and would inform the parameters of that new training regime.
