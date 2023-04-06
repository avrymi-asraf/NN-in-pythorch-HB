&rlm;

# עקרונות של רשתות  ע"י _pytorch_

מדריך בעברית לשימוש בספרייה 
_pytorch_


## מבנה
&rlm;
המדריך מחולק ל2 חלקים: החלק הבסיסי מסביר את העקרונות הבסיסים שאותם צריך בשביל לבנות רשת נויירונים. 
בחלק הזה נראה רק דוגמאות חלקיות, כיון שהמטרה היא רק להבין איך קורה תהליך יצירה ואימון של רשת נויירונים. 
בחלק המתקדם יש פירוט על כל רכיב ורכיב בפני עצמו. ההמלצה שלי היא לעבור על החלק הבסיסי, ורק לאחר מכן להעמיק לפי הצורך בחלקים השונים. 
### מדריך בסיסי
- [Tensors](Tensors.ipynb) טזנסור הוא הבסיס עליו בנוייה הספרייה. 
- [Neural_Networks](Neural_Networks.ipynb)מסביר את המבנה הבסיסי של רשתות נויירונים. 
- [Autograd_and_Backpropagation](Autograd_and_Backpropagation.ipynb) מסביר איך עובד תהליך הפיעפוע לאחור  - תהליך האימון ברשתות נויירונים ואיך ב_pytorch_ התהליך הזה קורה באופן אטומטי. 
### מדריכים מפורטים
- [Models](Models.ipynb)  מודלים זה לב הרשת נויירונים, נראה את הממשק של pytorch  לבניית מודלים
- [Dence_Layer](Dence_Layer.ipynb) השיכבה הבסיסית, שכיבה ליניארית פלוס פונקציית אקטיבציה 
- [Convolution_Layer](Convolution_Layer.ipynb)  שכבת קונבולוציה - היא משמשת בעיקר לרשתות העוסקות בתמונות 
- [Embedding_Layer](Embedding_Layer.ipynb)  שכבת הטמעה - מאפשרת להציג מילים בתור וקטורים במיימדים יותר גובהים
- [Optimizers](Optimizers.ipynb) סוגי האופטימייזרים השונים הקיימים, והשוואות בניהם. 
- [Loss_Functions](Loss_functions.ipynb) פונקציית העלות השונות וההבדלים בניהם. 
- [Language_models](Language_models.ipynb) כלים שימושיים למודלי שפה. 
- [Images_models](Images_models.ipynb) כלים שימושיים למודלים העוסקים בתמונות. 
- [Gan_Models](Gan_Models.ipynb) יצירת מודלים יצירתיים. 
- [Hyperparameters](Hyperparameters.ipynb) קביעת ההיפר פרמטרים במהלך אימון הרשת. 

### שונות
- [Visualztion](Visualztion.ipynb) כלים וטכינקות להמחשה של תהליך בניית הרשת ואימונה, תוך שימוש בסיפריית `plotly`. 
- [Data_prosessing](Data_prosessing.ipynb) תהליך יבוא וניקוי דאטא
- [Tools](Tools.py) כלים שונים. 
- [Guide](Guide.md) איך לתרום למדריכים. 
### עקרונות עבודה
- הידע המקדים הנדרש הוא הבנת הסינטקס של פייתון
- נשקיע הרבה בשביל לתת אינטואיציה  לאיך הדברים עובדים.
- המדריך יהווה פתח ללמידה עמוקה ואמתית, נמנע ככול האפשר מ"שקרים" גם אם הם נועדו להקל על ההסבר, נתן כמה שיותר הסבר לאיך המושגים באמת
- נשתמש בשפה אחידה. 


[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/avrymi-asraf/NN-in-pythorch-HB/blob/main/Autograd_and_Backpropagation.ipynb)