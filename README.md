# Unload_time_prediction

Each day a coffee chain routes trucks to deliver products to our stores to enable the business. To achieve this, there is an advanced optimization algorithm which determines the optimal sequence of stops for any
given route. A route is a complete sequence of stops in a specific order. One of the key inputs to the optimization algorithm is the expected unload time at a store. The unload time helps the
optimization algorithm determine the total duration of the route, i.e. total drive time + total unload time = total duration of a route.

The current estimate for unload time is resulting in high variance when comparing the planned route duration to the actual route duration. The planned unload time has been identified as the
key driver of the variance. If the unload time can be better predicted or estimated, then the optimized plan will better align to the executed plan, resulting in better planned routes.

Task here is to build a solution or model to address the problem stated above
