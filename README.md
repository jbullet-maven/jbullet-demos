jbullet-demos
=============

This is non-official mavenisation of jbullet library. See http://jbullet.advel.cz/ for original project details.

To run the demos, perform on clonned tree

```
mvn install
```

And pick one of following cmd to execute specific demo:

```
java -Djava.library.path=target/natives/ -cp target/jbullet-demos-20101010-SNAPSHOT.jar com.bulletphysics.demos.basic.BasicDemo
java -Djava.library.path=target/natives/ -cp target/jbullet-demos-20101010-SNAPSHOT.jar com.bulletphysics.demos.bsp.BspDemo
java -Djava.library.path=target/natives/ -cp target/jbullet-demos-20101010-SNAPSHOT.jar com.bulletphysics.demos.character.CharacterDemo
java -Djava.library.path=target/natives/ -cp target/jbullet-demos-20101010-SNAPSHOT.jar com.bulletphysics.demos.concave.ConcaveDemo
java -Djava.library.path=target/natives/ -cp target/jbullet-demos-20101010-SNAPSHOT.jar com.bulletphysics.demos.concaveconvexcast.ConcaveConvexcastDemo
java -Djava.library.path=target/natives/ -cp target/jbullet-demos-20101010-SNAPSHOT.jar com.bulletphysics.demos.dynamiccontrol.DynamicControlDemo
java -Djava.library.path=target/natives/ -cp target/jbullet-demos-20101010-SNAPSHOT.jar com.bulletphysics.demos.forklift.ForkLiftDemo
java -Djava.library.path=target/natives/ -cp target/jbullet-demos-20101010-SNAPSHOT.jar com.bulletphysics.demos.genericjoint.GenericJointDemo
java -Djava.library.path=target/natives/ -cp target/jbullet-demos-20101010-SNAPSHOT.jar com.bulletphysics.demos.movingconcave.MovingConcaveDemo
java -Djava.library.path=target/natives/ -cp target/jbullet-demos-20101010-SNAPSHOT.jar com.bulletphysics.demos.vehicle.VehicleDemo
```
