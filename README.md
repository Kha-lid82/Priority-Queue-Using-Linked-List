# Priority-Queue-Using-Linked-List
Priority Queue is more specialized data structure than Queue. Like ordinary queue, priority queue has same method but with a major difference. In Priority queue items are ordered by key value so that item with the lowest value of key is at front and item with the highest value of key is at rear or vice versa. So we're assigned priority to item based on its key value. Lower the value, higher the priority. Following are the principal methods of a Priority Queue. 

ALGORITHM OF THE PROGRAM

Step 1: Start
Step 2: First make a info NODE and front pointer=-1
Step 3: If(FRONT==NULL), then print “no more entry in queue” ,
             Else take appointment of patient and send it   
               if( front == NULL || item_priority < front->priority )
                {  tmp->link = front;
                  Front = tmp;}
                   else{
                   q = front;
                   while( q->link != NULL && q->link->priority <= item_priority ) q=q->link;
                   tmp->link = q->link;
                    q->link = tmp;}
Step 4: Then ask user that he wants to viewlist or continue 
Step 5: For viewing list you want to assing  *ptr pointer
              Then traverse it and print the information one by one
Step 6: Stop

*DISCLAIMER if conio.h library or clrscr(); function gives error ,then remove both line from code program will run properly without error :)   
