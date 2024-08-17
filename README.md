# kmer-nodes

- go program making specific kmers and then extracting those with the specific terminal edges.
- for the mers and also to sort out and filter the kmers with the specific terminal edges. 
- it will first create the kmers and then will give out those kmers for which the terminal ends are mapping to the specific for implementation into the graph edges.
- you can chain this using the concurrency for extracting the complete graph edges and creating a map like
```
func gochain (input <- chan string, kmer <-chan int, terminaltypes <- chan string) {
 / put the function here.
}
```

Gaurav Sablok 
