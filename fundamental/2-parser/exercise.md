# Parser

## 1. Parse String to Int Slice
> Given the input string: `"1,2,3,4,5"`. Split it and convert it into a slice of integers: []int.

#### Expected Output:
```
[]int{1, 2, 3, 4, 5}
```

#### Starter Code:
```
import "strings"
import "strconv"

func ParseInts(input string) []int {
	// TODO: split the string, convert to int, return slice
	return []int{}
}
```

## 2. Parse Student Scores
> Given a string like `"Ali:80,Budi:70,Ali:90"`,
> return a map of student names to a list of their scores.

#### Expected Output:
```
map[string][]int{
  "Ali": {80, 90},
  "Budi": {70},
}
```

#### Starter Code:
```
func ParseScores(data string) map[string][]int {
	// TODO: split by comma, then by colon
	return map[string][]int{}
}
```

## 3. Parse Student Scores
> Given the map from Exercise 2, return a new map with the average score for each student.

#### Expected Output:
```
map[string]float64{
  "Ali": 85.0,
  "Budi": 70.0,
}
```

#### Starter Code:
```
func AverageScores(scores map[string][]int) map[string]float64 {
	// TODO: compute average for each student
	return map[string]float64{}
}
```