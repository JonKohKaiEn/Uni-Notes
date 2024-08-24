# While loops
```
while (condition){
	/*
	loop body goes here

	there must be something in here that causes the loop condition to be false
	(so that the loop can be exited)
	*/
}
```

# For loops
```
// different ways of doing a for loop

for (int i = 0; i < n; i++){
	// loop body
}
----------------------------
int i = 0;
for (; i < n; i++){
	// loop body
}
----------------------------
int i = 0;
for (; i < n;){
	// loop body
	i++;
}
```