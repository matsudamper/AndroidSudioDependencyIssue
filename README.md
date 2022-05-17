# Case
## Case1 legacy-preference-v14
- sub module has 'implementation("androidx.legacy:legacy-preference-v14:1.0.0")'

![image](https://user-images.githubusercontent.com/9250063/168795752-3f10dae9-dedd-43aa-a5d2-07082112289c.png)

## Case2 firebase-bom
- app module has firebase-bom.
- sub module has 'implementation("com.google.firebase:firebase-config:21.0.2")'
  - same for 'implementation("com.google.firebase:firebase-analytics:21.0.0")'

![image](https://user-images.githubusercontent.com/9250063/168795710-916472f1-31dc-4eb6-8d82-b3a6e1396f9a.png)

# Code Jump
class AppCompatActivity extends FragmentActivity  
this source is `appcompat-1.4.1-sources.jar`  
![image](https://user-images.githubusercontent.com/9250063/168796001-b3b18e05-ec74-4e56-b748-7ab2aa7abba9.png)

`class FragmentActivity extends ComponentActivity`  
this source is `fragment-1.0.0-sources.jar`  
![image](https://user-images.githubusercontent.com/9250063/168796246-e72359ff-14e3-44aa-ba3d-84d504a0820d.png)
