# User profiling

This code creates 1000 synthetic users: 
1. It defines the set of categories-apps and traffic percentage for each user based on the power-law distribution of the inter and intra-category probabilities. 
2. It assigns the corresponding traffic to each user using mobile app traces.
3. It profiles each user based on DNS traffic. 