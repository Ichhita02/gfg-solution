# gfg-solution
occurence of an integer in a linked list
class Solution
{
    public:
    int count(struct node* head, int search_for)
    {
      int count=0;
      node *temp=head;
      while(temp)
      {
          if(temp->data== search_for)
          {
          count++;
      }
      temp=temp->next;
    }
      return count;
    //add your code here
    }
};
