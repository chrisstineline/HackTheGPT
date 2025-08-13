# HackTheGPT
### A repository containing code and documentation related to testing 
### ChatGPT model 5 and its vulnerabilities. 


# HackTheGPT - IhearyoulikeIPs
**Introduction: I like polyrhythms (Ref 1), and ChatGPT likes Polymorphism.** 

I'll be using Polymorphism as a reference because of the multi-layer aspect to it of: 

Flexibility -> Code can be written ambiguously and thereby multipurpose and able handle a variety of objects, without needing to know specifics to compile

Code reusability -> The ambiguous generic code operates on a base class, working with any derived classes 

Abstraction -> Allowing for not having specific details of different objects = common behavior is allowed


### Model 5 and results
Notice: Because of risks by replication, the conduct and specific prompts, which lead to the model producing the results it did, everything is heavily censored or completely left out. These are directly related to also protecting the potential victims of bad actors, who are looking to exploit the AI and them. 

Using Model 5 (free version) affects the results given when prompting for new entries -> The model provides a better structure, seemingly finding targets which are high risk, and is overall being selective regarding data. (Comparison to Model 4 (free version)) 


Reusing prompts and results by only prompting "new list" also keeps the model on track, and continuously producing the same level of data. This inherited 

## What was done
Based on a prompt asking for a realistic scenario of a security breach, going through the scenario with specific steps and slow introduction to tools or services, the machine referenced back to said tools or services, when prompted for: “Show an example of the type of code I would see in a script being inserted into a system to effect a docker image and cluster” 

The result was a 75% done script for creating contact with a Docker container and doing a direct transfer of data back. This indicating something about the model:

-	It can be pointed in a direction and guided around rules for usage
-	It will prefer real life examples compared to make up information

  
Guiding the model further by slowly changing the prompts, before getting a “best product”, the repetitive prompting of “new list” was ensured, and it continuously created new examples, all with live IPs and matching ports. 

 

 
Ref 1: https://listenonrepeat.com/?v=SthcxWPXG_E#I_heard_you_like_polyrhythms
