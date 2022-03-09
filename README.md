# 2665_MakingMaze

made by Jaehyeok Choi

## Welcome to Jaehyeok's github!

## What is the problem?

![image](https://github.com/Choi-JaeHyeok-21500749/2665_MakingMaze/blob/main/2665_pro.PNG)

## What Algorithm should I use?

Graph Algorithm , bfs

## What was the key point and the hard part?

Because we want less black room while reaching the end point , black room is the cost.

So, in here , we don't have to revisit some place if we already visit that place with less black room we passed.

By using in visit array , this can be solved.

If visit[next loc][next loc ] is bigger , which means we visited that location but there is more efficient(less black room passed) way , we visit that array and change the 
value of nexloc with current loc value.

If visit [next loc ][ next loc] is smaller , we don't have to visit that place.

Som the answer would be visit[end point][end point]

Be aware that we have to do bfs until q is empty to find min answer.

I think dijkstra will work if we see white room as cost 0 and black rrom as cost 1.

## Where can I get more help, if I need it?

You can contact me through email, which is wogur7496@gmail.com.
Thank you for visiting this github!
