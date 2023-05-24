# Encapsulation and Data Hiding

- When an object is asked to do something, the result may be a change in its state.
- Example: if the dog is told its new favorite toy, its state has changed.
- The **only way** an object's state can be **changed** is by asking it to do something. It could be something simple:

```java
aDog.setName("Bruiser")
```

or something complex:

```java
aDog.buryBone()
```

- This is also called **encapsulating** the data.
