

# Aptos graffiti wall 

- Live: [werewolfandwitch.xyz](https://werewolfandwitch.xyz/)

## Description
This feature was introduced in one of the updates in the Werewolf and Witch game, a decentralized game based on the Move smart contracts. Users can rent a pixel in a pixel map and change the color of that pixel which allows them to draw a full-sized image composed of pixels. During the rent time, other users cannot overwrite the pixel unless given an admin authority.

## Cloning the repository
```git clone https://github.com/werewolfandwitch/aptos-pixel-graffiti-wall.git```
Change the file path in dependencies and update the addresses

## Initialize
Initialize with ```aptos init``` in the ```aptos-pixel-graffiti-wall``` folder you just cloned

## Compile
```aptos move compile --named-addresses war_land=default```

## Publish
```aptos move publish --named-addresses war_land=default```


<br/>

License
=======

    Copyright 2023 Werewolf and Witch

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.


