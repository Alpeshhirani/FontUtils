# FontUtils
Easy way to set Font Style to text in android. 
============
```
Typeface regular, bold;

 @Override
    protected void onCreate(@Nullable Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.Layout);
        
        regular= FontUtils.createTypeface(this,false);
        bold= FontUtils.createTypeface(this,true);
        FontUtils.setFont("Enter Layout Name here",regular);
        
        }
```
