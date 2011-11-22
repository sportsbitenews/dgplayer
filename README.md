DGPlayer
========

### Interface
```java
interface Player {
    on(event, callback);           // event: play, pause, volume 
    off(event, callback);
    
    property string state;          // buffering, playing, or paused
    property number bufferProgress; // 0-100
    property url coverArt;
    property number volume;         // 0-100
    property string songTitle;
    property string songArtist;
}
```