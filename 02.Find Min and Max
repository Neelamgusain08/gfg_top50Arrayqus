class Compute 
{
    static pair getMinMax(long a[], long n)  
    {
    // initially initialize min and max =0 
       int min=0; 
       int max=0;
       //for loop for traversing
       for(int i=1;i<n;i++){
           if(a[min]>a[i]){
               min=i; //if a[0] is greater than a[i] then min  will change from a[0] to a[i]
           }
            if(a[max]<a[i]){
                max=i; //if a[0] is smaller than a[i] then max will change from a[0] to a[i]
                
            
           }
         
        
       }
       return new pair(a[min],a[max]); //return the pair of min max 
    }
}
