
This is an atomic component that shows a single row from schedule.

### Example: Project started late but projected to complete early

```js
<TreeItemRow 
  progress='20' 
  scheduledDate='2019-11-01' 
  completedDate='' 
  start='0' 
  scheduled='300' 
  started='0' 
  yet='20' 
  comp='50' 
  project='190' 
  early='40'
  behind='0' 
  late='0' 
  notes='Started late but projected to complete early'
/>  
```

### Example: Project started ontime and projected to complete ontime

```js
<TreeItemRow 
  progress='20' 
  scheduledDate='2019-11-01' 
  completedDate='' 
  start='0' 
  scheduled='400' 
  started='0' 
  yet='0' 
  comp='100' 
  project='300' 
  early='0'
  behind='0' 
  late='0' 
  notes='Started ontime and projected to complete ontime'
/>
```

### Example: Project scheduled later started ontime and projected to complete ontime

```js
<TreeItemRow 
  progress='20' 
  scheduledDate='2020-01-01' 
  completedDate='' 
  start='50' 
  scheduled='400' 
  started='50' 
  yet='0' 
  comp='100' 
  project='300' 
  early='0'
  behind='0' 
  late='0' 
  notes='Started ontime and projected to complete ontime'
/>
```

### Example: Project scheduled later started early and projected to complete late

```js
<TreeItemRow 
  progress='20' 
  scheduledDate='2020-01-01' 
  completedDate='' 
  start='50' 
  scheduled='400' 
  started='0' 
  yet='0' 
  comp='100' 
  project='300' 
  early='0'
  behind='100' 
  late='0' 
  notes='Scheduled later started early and projected to complete late'
/>
```

### Example: Project scheduled later started early and projected to complete late

```js
<TreeItemRow 
  progress='20' 
  scheduledDate='2020-01-01' 
  completedDate='' 
  start='0' 
  scheduled='400' 
  started='0' 
  yet='0' 
  comp='100' 
  project='300' 
  early='0'
  behind='100' 
  late='0' 
  notes='Scheduled later started early and projected to complete late'
/>
```

### Example: Project starting late, projected to end late and ending even later

```js
<TreeItemRow 
  progress='100' 
  scheduledDate='2019-01-01' 
  completedDate='2020-01-15' 
  start='0' 
  scheduled='200' 
  started='0' 
  yet='50' 
  comp='100' 
  project='50' 
  early='0'
  behind='50' 
  late='50' 
  notes='Starting late, projected to end late and ending even later'
/>
```

### Example: Project starting ontime, completed a little late

```js
<TreeItemRow 
  progress='100' 
  scheduledDate='2019-01-01' 
  completedDate='2020-01-15' 
  start='0' 
  scheduled='200' 
  started='0' 
  yet='0' 
  comp='200' 
  project='0' 
  early='0'
  behind='0' 
  late='50' 
  notes='Project starting ontime, completed a little late'
/>
```

### Example: Unlikely project showing all possible parts

```js
<TreeItemRow 
  progress='20' 
  scheduledDate='2020-01-01' 
  completedDate='' 
  start='0' 
  scheduled='300' 
  started='0' 
  yet='50' 
  comp='50' 
  project='50' 
  early='50'
  behind='50' 
  late='50' 
  notes='showing all possible parts'
/>
```