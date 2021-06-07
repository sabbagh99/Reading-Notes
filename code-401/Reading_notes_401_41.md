# Intent Filters

## Allowing Other Apps to Start Your Activity

### If your application provide uploding imeges shere masseges and so you need to allow other user start your activity to do so you need to use intent filters by support the [ACTION_SEND](https://developer.android.com/reference/android/content/Intent#ACTION_SEND) intent


## Start using Intent Filters :

#### 1.add an <[intent-filter](https://developer.android.com/guide/topics/manifest/intent-filter-element)> element in your manifest file.

#### 2. Add an Intent Filter Action (ACTION_SEND) / Data ( <data>) /  Category (CATEGORY_DEFAULT).

#### 3. Handle the Intent in Your Activity 
##### we need to add this code in our on create method:

@Override
protected void onCreate(Bundle savedInstanceState) {
    super.onCreate(savedInstanceState);

    setContentView(R.layout.main);

    // Get the intent that started this activity
    Intent intent = getIntent();
    Uri data = intent.getData();

    // Figure out what to do based on the intent type
    if (intent.getType().indexOf("image/") != -1) {
        // Handle intents with image data ...
    } else if (intent.getType().equals("text/plain")) {
        // Handle intents with text ...
    }
}

#### 4. Return a Result 
##### If you want to return a result to the activity that invoked yours, simply call setResult() to specify the result code and result Intent
.