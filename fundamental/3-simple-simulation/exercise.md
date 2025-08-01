# Simple Simulation

## 1. Simple ATM Simulator
> Given a total amount (e.g., 275000), calculate how many bills of each denomination are needed.
> Use denominations: 100k, 50k, 20k, 10k, 5k, 1k.

#### Expected Output:
```
map[int]int{
  100000: 2,
  50000: 1,
  20000: 1,
  5000: 1,
}
```

#### Starter Code:
```
func MoneyChanger(amount int) map[int]int {
	denominations := []int{100000, 50000, 20000, 10000, 5000, 1000}
	result := map[int]int{}
	// TODO: implement logic
	return result
}
```