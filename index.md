<p><a target="_blank" href="https://app.eraser.io/workspace/VHoEELSGFVNGy5pgxreO" id="edit-in-eraser-github-link"><img alt="Edit in Eraser" src="https://firebasestorage.googleapis.com/v0/b/second-petal-295822.appspot.com/o/images%2Fgithub%2FOpen%20in%20Eraser.svg?alt=media&amp;token=968381c8-a7e7-472a-8ed6-4a6626da5501"></a></p>

# Events Storming
![image.png](/.eraser/VHoEELSGFVNGy5pgxreO___xqWYKd9ntEePv6FaUQV5R3VPmYW2___I49E8Fz5-dAMKC3YhRCCS.png "image.png")



### Actors


![image.png](/.eraser/VHoEELSGFVNGy5pgxreO___xqWYKd9ntEePv6FaUQV5R3VPmYW2___CHDSmemP_okSiwrIMxF1x.png "image.png")

### Events
![image.png](/.eraser/VHoEELSGFVNGy5pgxreO___xqWYKd9ntEePv6FaUQV5R3VPmYW2___mdCXVWcodldRmCaRBo1wf.png "image.png")

The events that's happened in your business



### Commands
![image.png](/.eraser/VHoEELSGFVNGy5pgxreO___xqWYKd9ntEePv6FaUQV5R3VPmYW2___cramkFrTVpPjKYb3WFm87.png "image.png")

### Policies
![image.png](/.eraser/VHoEELSGFVNGy5pgxreO___xqWYKd9ntEePv6FaUQV5R3VPmYW2___yipn45Zt99VBxOwOsIO8C.png "image.png")

### Hotspots
![image.png](/.eraser/VHoEELSGFVNGy5pgxreO___xqWYKd9ntEePv6FaUQV5R3VPmYW2___0CDRYPkRKFYogAaU5Cqrt.png "image.png")

### External Systems
![image.png](/.eraser/VHoEELSGFVNGy5pgxreO___xqWYKd9ntEePv6FaUQV5R3VPmYW2___9_NwL2gL0UvufsnMzJioY.png "image.png")

### Query Models
![image.png](/.eraser/VHoEELSGFVNGy5pgxreO___xqWYKd9ntEePv6FaUQV5R3VPmYW2___Lr9KU31axce3KhXicZOZR.png "image.png")

### Aggregates
![image.png](/.eraser/VHoEELSGFVNGy5pgxreO___xqWYKd9ntEePv6FaUQV5R3VPmYW2___LBazAjNkUaAOKnNmoCv_0.png "image.png")

## Practice
Let's build a dead simple todolist application.

The idea is user can see the overview of the tasks they have to do everyday. We'll have 4 tabs in the application:

The 1st one:

- Task creation box with default category
- List of pending tasks ( in list with remove/mark done button )
- List of completed tasks ( in list )
- List of categories ( display as a chip ) -> if user click on it list of tasks will be filter by category ( user can select multiple categories )
The 2nd one:

- Category creation box
- List of category
The 3rd one:

- Settings:
    - Default Category
    - Pending Tasks limit ( number of pending tasks )
- Reset Data:
    - Clear all tasks button
The 4th one:

- Statistic View Type Switch
    - Table
    - Chart
- Statistic Filter
    - Time Range: all the time(default), specific date, date range
- Statistic in table format
    - Total Task created
    - Total Completed tasks
    - Total Pending tasks
- Statistic in chart format
    - Total Task created
    - Total Completed tasks
    - Total Pending tasks


## Events






![image.png](/.eraser/VHoEELSGFVNGy5pgxreO___xqWYKd9ntEePv6FaUQV5R3VPmYW2___UBf0cnq1wfChIBFEL1Zsw.png "image.png")



## Events & Actors & Commands & Policies
### 1. 1st tab Screen : Tasks
#### 1.1.User **Open 1st tab**
![image.png](/.eraser/VHoEELSGFVNGy5pgxreO___xqWYKd9ntEePv6FaUQV5R3VPmYW2___l_LCjkcyGwz-RAO9BxUJR.png "image.png")

#### 1.2.User **Create new task**


![image.png](/.eraser/VHoEELSGFVNGy5pgxreO___xqWYKd9ntEePv6FaUQV5R3VPmYW2___GhJylb7WAkGTZ9itxYlNe.png "image.png")

#### 1.3.User **Remove a  task**
![image.png](/.eraser/VHoEELSGFVNGy5pgxreO___xqWYKd9ntEePv6FaUQV5R3VPmYW2____7CEAbaf5mL6kMOBNZr90.png "image.png")

#### 1.4.User **Mark a task as done**


![image.png](/.eraser/VHoEELSGFVNGy5pgxreO___xqWYKd9ntEePv6FaUQV5R3VPmYW2___S-15drSeS9ZnqVvEz1rCO.png "image.png")

#### 1.5.User **Apply Category Filter**
![image.png](/.eraser/VHoEELSGFVNGy5pgxreO___xqWYKd9ntEePv6FaUQV5R3VPmYW2___koXQGgGn12iNUmIVeSqgt.png "image.png")

### 2. 2nd tab Screen : Categories
#### 2.1. User **Open 2nd tab**
![image.png](/.eraser/VHoEELSGFVNGy5pgxreO___xqWYKd9ntEePv6FaUQV5R3VPmYW2___SMVCeF9xgWZEnRj3Yo5Sz.png "image.png")

#### 2.2. User **Create category**


![image.png](/.eraser/VHoEELSGFVNGy5pgxreO___xqWYKd9ntEePv6FaUQV5R3VPmYW2___a7lowxAnfNRxZOahq1pI0.png "image.png")



#### 2.3. User **Remove category**


![image.png](/.eraser/VHoEELSGFVNGy5pgxreO___xqWYKd9ntEePv6FaUQV5R3VPmYW2___bE7Niz5UJdm1pka2wKoyh.png "image.png")



## 3. 3rb tab: Setting


#### 3.1. User **Open Setting Tab**


![image.png](/.eraser/VHoEELSGFVNGy5pgxreO___xqWYKd9ntEePv6FaUQV5R3VPmYW2___nxo72XrvAw0CeOioOsOq1.png "image.png")

#### 3.2. User **Update Setting**
![image.png](/.eraser/VHoEELSGFVNGy5pgxreO___xqWYKd9ntEePv6FaUQV5R3VPmYW2___BpEiyyVFfP583_uP7MiC8.png "image.png")

#### 3.3. User **Clear all tasks**
![image.png](/.eraser/VHoEELSGFVNGy5pgxreO___xqWYKd9ntEePv6FaUQV5R3VPmYW2___vq-crCtEqyIpTlUUAc_sk.png "image.png")

## 4. 4th tab: Statistic


#### 4.1. User **Open Statistic Tab**
If Display Rule is not set

![image.png](/.eraser/VHoEELSGFVNGy5pgxreO___xqWYKd9ntEePv6FaUQV5R3VPmYW2___n4_E8WANKUtcQPFXFLUem.png "image.png")



If Display rule is Table View

![image.png](/.eraser/VHoEELSGFVNGy5pgxreO___xqWYKd9ntEePv6FaUQV5R3VPmYW2___AbgcG6kPPzsi5TdpB10qh.png "image.png")



If Display rule is Chart View

![image.png](/.eraser/VHoEELSGFVNGy5pgxreO___xqWYKd9ntEePv6FaUQV5R3VPmYW2___VGu0-E3MMYbTCwJJCYCFc.png "image.png")

#### 4.2. User **Switch View Type**
User Switch View Type From Table View to Chart View



![image.png](/.eraser/VHoEELSGFVNGy5pgxreO___xqWYKd9ntEePv6FaUQV5R3VPmYW2___u4FxCEV3vz-4CRo0l9eZC.png "image.png")



User Switch View Type From Chart View to Table View

![image.png](/.eraser/VHoEELSGFVNGy5pgxreO___xqWYKd9ntEePv6FaUQV5R3VPmYW2___03hdecz8PctLBnflxDvM8.png "image.png")

#### 4.3. User **Apply Statistic Filter**


![image.png](/.eraser/VHoEELSGFVNGy5pgxreO___xqWYKd9ntEePv6FaUQV5R3VPmYW2___XVY-R0Xp2ZuJeLsULdcCl.png "image.png")





<!--- Eraser file: https://app.eraser.io/workspace/VHoEELSGFVNGy5pgxreO --->