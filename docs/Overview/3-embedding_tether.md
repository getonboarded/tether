Tether is designed to be embedable in other libraries.

There is one basic things you have to do to create an embedded Tether:

- Set the `classPrefix` of the tethers you create.  That prefix will replace `'tether'` in
all of the classes.  You can also disable classes you don't intend on using with the `classes`
option.