回溯法
void process(int start,ArraryList<...> list,.......)
{
   if(...==...){
   ....
   return
   }
   if(){
   return
   }
   for(int i=start;i<..;i++){
   list.add()
   process(i/i+1/0)//如果允许重复下一个start从i开始。不允许重复就从i+1开始，如果要求全排列，即不只是求组合排列的顺序不一样也要区分时，start直接取开始的值
   list.remove(list.size()-1)
   }
}
