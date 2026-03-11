# 51. WSJF or the art of prioritization at Taxiter

WSJF or the art of prioritization at Taxiter

[Fibonacci numbers, T-shirt sizes, business scores, time dependency, USP, effort, impact, estimates]

We use one of the conference rooms. Because Bea made a reservation, we can go in within a few minutes. I've never been particularly fond of Salvador Dali's old master-style paintings. However, the swans reflect the elephants themselves as posters on the front wall in such an irritating way that I have to pause for a moment to realize that Anna's head, which is gallantly pushing its way into the picture at this moment, is not part of Dali's staging.
Anna: Hey, you guys are making such strange faces. Do I look funny?
Me: No, just surreal.
For quite a few people, the mere mention of the word "mathematics" causes a shift in reality in their brains. Like clocks in another Dali painting, numbers begin to melt when you stare at them long enough. All the more reason for me to apologize at this point for having to ask you, dear reader, to do some math. WSJF, the method for prioritization, has to be fed with numbers.
This requires knowledge of the so-called simplified Fibonacci numbers. Namely 1, 2, 3, 5, 8, 13, 21, 34, 55, 89, 144 ... The series can be continued indefinitely, but the numbers relevant for WSJF are 1 to 13 inclusive, or 21 at most, i.e. six or seven in total. For the WSJF, you can work directly with these numbers or assign them to T-shirt sizes as follows: XS = 1, S = 2, M = 3, L = 5, XL = 8, XXL = 13, XXXL = 21.
Using T-shirt sizes is more intuitive and therefore easier. However, the T-shirt sizes must be converted back into numbers for further mathematical processing later on, which can mean an extra step.
Bea and Anna prefer to work with T-shirt sizes. They are familiar with this method, having used it in the past, but without linking it to Fibonacci numbers.
As a reminder, the prioritization of tasks according to the business: First place – integration of the amendment to the law. Second place – acceleration of the platform. Third place – optimization of the chatbot. Then there are five more, which are omitted here for the sake of simplicity.
The integration of the amendment to the law was given the highest priority by the business, i.e., amendment to the law = XXL or 13.
Accelerating the platform comes in second place, so: platform = XL or 8.
Then optimizing the chatbot in third place, i.e., chatbot = L or 5.
Now you may be wondering what to do if six numbers from 1 to 13 are not enough because there are more than six tasks. First, the Fibonacci sequence is infinite, so you will not run out of numbers. Secondly, more than six tasks in one go are too many anyway. Especially since the three tasks shown here are too big and therefore need to be broken down into subtasks, which in turn need to be prioritized. But more on that later.
There are now three business scores (BS) for the business: legislative amendment = XXL, platform = XL, chatbot = L. Now Bea and Anna, as competence leads, are required to evaluate the three tasks according to the following additional criteria:
First, time dependency (TD) – how important is the time factor in completion? Is there a date by which the adjustment must be made to avoid penalties? What will it cost the company if delivery is delayed?
Second, impact (I) on the USP (unique selling proposition) – to what extent does completion have a positive effect on the company's unique selling point?
Finally, thirdly, the effort (E) in terms of working hours required for completion – again, estimated using T-shirt sizes.
I now ask Bea and Anna to determine the three missing values for each of the three tasks. Both consider the time dependency for the amendment to the law to be high, i.e., also XXL. Bea rates the platform TD as L, but Anna rates it as M. Both rate the chatbot TD as M. The impact of integrating the amendment to the law for taxis – Bea: L, Anna: XL. The impact of accelerating the platform – both: L. Impact on the chatbot – unanimous: XXL. Now the time effort required for completion. Amendment to the law E – unanimous: M. Platform E – unanimous: XXL. Chatbot E – Bea: S, Anna: M.


It took Bea and Anna just under half an hour to arrive at the above result.
How long did a comparable process take in the team before? I ask.
Bea: At least an hour, often longer.
Me: You only prioritized three tasks, but it wouldn't have taken you much longer to do six, right?
When they both nod, I explain the next steps for arriving at the actual result using WSJF. First, replace the T-shirt sizes with the corresponding Fibonacci numbers (if there are two values, the average can be taken. To avoid decimal places, values can be rounded up). The table then looks like this:


Now, the following formula applies: BS + TD + I = Delay Costs (DC). And DC is finally divided by the Effort (E) = Prioritization Value (P).
That's all there is to the math. Third grade elementary school, I'd say.
Anna: Super simple.
Bea: And probably super useful.

The result is as follows:


From a purely mathematical perspective, the prioritization is clear: first, the integration of the amendment to the law (P-value: 11), then the optimization of the chatbot (P-value: 7). And third, quite far down the scale, the platform (P-value: 1.3).
The latter is so clear that I wouldn't question it, I explain to Bea and Anna. However, assuming that first and second place were even closer together in terms of values, it might make sense to discuss the priorities again within the team.
Anna: Aren't we going to do that next Monday anyway?
Me: Yes, but more for informational purposes with the possibility of well-founded objections. Because it shouldn't be about consensus. These are estimates. Not all developers have to agree. However, well-founded additions and objective criticism are most welcome. If estimated values are challenged by well-founded criticism, they should of course be readjusted afterwards. That's part of best practice. But opinions or vague preferences should not play a role.
Bea: Isn't that obvious?
Me: No. Most people prefer doing one thing over another. The influence of preferences should therefore be excluded when prioritizing. But that is precisely one of the strengths of the WSJF calculation.
Anna: So, as little gut feeling as possible?
Me: Your gut feeling as competence leads was required. You made estimates that are naturally based on experience, but can still only be the best possible assumptions. After all, all three tasks are ventures into the at least partially unknown. You don't know, and can't know, how long each one will take to complete. However, it is highly likely that your estimates will be pretty accurate. Whether they are very accurate, reasonably accurate, not quite accurate, or quite inaccurate, we will definitely know later, namely when everything is completed, tested, and in operation.
What would Salvador Dali have said about this? He was known for his fondness for psychoanalysis. However, he is also said to have been moved by the beauty of numbers. With WSJF, in principle, any project can be prioritized, from artistic works to political decisions.

Learned in Chapter 51:
WSJF, the method for prioritizing jobs, begins with estimates. For example, the importance for the business. This is followed by assessments of the development effort, etc. Estimates based on T-shirt sizes are popular and intuitive. However, these must be translated into numbers for mathematical processing. Therefore, it is preferable to start with numerical estimates right away. The Fibonacci series has proven itself useful for this purpose. The series 1, 2, 3, 5, 8, 13, 21 is commonly used. The increasing jumps aptly mark the increase in effort with increasing size/complexity.
The following aspects must be estimated for each task: Business Score (BS), Time Dependency (TD), Impact (I), Effort (E). BS refers to the value for the business. TD refers to the time factor. I stands for the impact of the completed task on the company. The sum of BS, TD, and I results in a total that is referred to as delay costs (DC). DC divided by effort (E) gives the prioritization value (P).
All values must be stored in an estimation history so that we can learn from them and refine future estimates.