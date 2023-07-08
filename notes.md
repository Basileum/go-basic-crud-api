# Notes - Basic CRUD API in Go (go-basic-crud-api)

## What I learned
### How we can handle slices 
With [this article](https://go.dev/blog/slices-intro)
```go
type Movie struct {
	// Movie type definition
}

// Movies slice initialization
var movies []Movie

// Recompose the slice
movies = append(movies[:index], movies[index+1:]...)
```
On last code line : 
```go
movies[:index]
```
Return a slice from the first movies slice elements until index (without the index one)

```go
movies[index+1:]
```
Return a slice from the movies slice index+1 element until last one

```go
append(movies[:index], movies[index+1:]...)
```
Return the append of the two slices



