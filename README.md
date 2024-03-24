#### ABM-schelling-model-with-moving-to-friend-choice-available

<img width="892" alt="image" src="https://github.com/Yiqiu-W/ABM-schelling-model-with-moving-to-friend-choice-available/assets/164640614/f48cf30a-c917-4672-97c5-9782e599eb6c">


##### Answers:

##### 1
##### In the original segregation model where unhappy agents move randomly untill they find ideal patchs, after running 100 ticks(with denisty equals to 70% 80% 90%), the percent-similar scores all exceed 70%. When the density is 90%, the persent-similar score is significently(***) higher than those of 70% density and 80 % density. But the persent-similar scores of 70% density and 80% density are similar and their comparision is not significant(NS)/not very significant(*)

##### In the modified model, in the beginning, agents create links with similar agents on their neighbor patches and these agents become their friends/contacts. Besides using "random-move", agents can also move based on suggestions from a friend/contact(who is similar to them, if they have at least one friend/contact), after running 100 ticks(with density equals to 70% 80% 90%), the percent-similar scores are all slightly lower than 70%(but greater than 65%).

##### This suggests that the modified model is in general less segregated than the original model.

##### Although "move-to-friend" sounds like a more purposeful(the agents know there should be at least one similar agent near the moved-to patch) strategy than just moving randomly, it does not necessarily guarantee "a better move". By "a better move", we mean that there are more similar agents there than the patch the agent was on before. "move-to-friend" only makes sure that the agent should have one neighbor agent who is similar to it, but it could be that an agent originalyl have 2 similar agents near(not happy), but then have only 1 similar agent after moving who is exactly the friend/contact it just contacted. Then this should be "a bad move".

##### When agents are using "random-move", it just settle down on any empty patch in the whole environment.

##### If we look at the happy status after moving, the two strategies would be quite similar.

##### Since agents with friends/contatcs always choose to be neighbors of a friend/contact(as long as there is empty patch available), it is more likely that agents together with their contacts would form ideal neighborhood which is small in size. That is, since our agents could only have limited numbers of contacts(even if one agents is similar to me, it is not one of my contatcts if it lives far away from me in the beginning), agents with friends/contatcs tend to live with (at least one) contact (s), if possible. The neighborhoods where (at least one of) their contact(s) live(s) are more likely to be their moving choice than any other neighborhood with empty patches. And as long as those small neighborhoods make them happy, they would not move to a larger neighborhood with more similar agents.

##### In the original model, no agent is constrained by contacts.Small neighborhood where similarity is high should be more common in the modified model than in the original model(where large neighborhood where similarity is high should be more common). So the percent-similar score of the modified model is lower than that of the original model.

##### 2
##### In the modified model, the percent-similar scores continue increasing with the density increasing from 70% to 80% and then to 90%. The comparison between them are all significant(***). We have already argued that small neighborhood where similarity is high should be more common in the modified model in question one. When the density is low, these small neighborhoods are more likely to scatter all over the whole environment so it is hard to find severly segregated area(the area is big in size and many similar agents live there). When the density is high, there is higher chance that some small neighborhoods are located just next to each other and become a large neighborhood where similarity is high. Then the percent-similar score is higher and higher level of segregation could be found.
