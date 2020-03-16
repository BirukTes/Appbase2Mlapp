# Appbase2Mlapp
Convert appbase class m code app 2 mlapp (app designer)

### How it works?
- This app works by evaluating the appbase/handle class m code and copying the components (some), and serialising them to MLAPP. 

### Usage
1. Select m file
   - Remove/replace any params for conversion, as of now.
2. Click Get Props

3. Group components that you would like to be grouped

4. Click convert

5. Make sure to open the mlapp in app designer, for the code to generate  

#### Tips:
- The process can be trial and error, such as when you open the converted app, it will also run the old app. This might be because some of the components such as uidropdown are still referencing the handle, thus in-order to get rid of the referenced old app, you will add a new component in App Designer and it will be saved separately.   

` V1.3`
