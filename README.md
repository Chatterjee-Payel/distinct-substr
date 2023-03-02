# distinct-substr
int fun(string s)
{
    //code here
    set<string>st;
    for(int i=0;i<s.size()-1;i++){
        st.insert(s.substr(i,2));
        
    }
    return st.size();
    
}
