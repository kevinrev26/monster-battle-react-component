# react-monstereos-monster-battle

## How to install
Execute:
```
npm install --save https://github.com/VertexStudio/monster-battle-react-component
```
or
```
yarn add https://github.com/VertexStudio/monster-battle-react-component
```

Then, install its peer dependencies:
```
npm install --save react@16.x three@^0.96.0
```

## Usage

```javascript
import React from 'react'
//import monster3D from './assets/models/vampire.gltf'
import myMonster from './assets/models/bear.gltf'
import enemyMonster from './assets/models/butterfly.gltf'
import Arena3D from 'react-monstereos-battle'

const Arena = () =>
    <Arena3D
        myMonster={myMonster}
        enemyMonster={enemyMonster}
        size={{ width: "100%", height: "100%" }}
        background={{ alpha: 1 }}
    />
```

### Component properties
| Name             | Type     | Default                              | Description                                                                                        |
| ---------------- | -------- | ------------------------------------ | -------------------------------------------------------------------------------------------------- |
| myMonster           | `string` |                                      | String containing the path to monster object .gltf                                                                                      |
| enemyMonster             | `string` |                                      | String containing the path to enemy monster object .gltf                                                          |
| size           | `object` | `{ width: "100%", height: "100%"}`                               | size of the arena |
| background         | `object` | `{ alpha: 1 }`               | Opacity                                                                        |


## Run demo

1. `git clone https://github.com/VertexStudio/monster-battle-react-component`.
2. `cd monster-battle-react-component`.
3. `npm install`.
4. `npm start`.
5. Demo running at `http://localhost:3000/`. 
