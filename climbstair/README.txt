Project: climbstair

API included: stridesRequired

/stridesRequired:
Input type: JSON
sample: 
{
    "numberOfSteps": [
        17,17
    ],
    "stepsPerStride": 3
}

Output type:JSON 
14

This API calculates the number of strides required to cover the flight of steps.
It is calculated using the number of steps covered in a single stride.
If there are 17 steps and stepsPerStride=3, then 5 strides are required to complete 6 steps and 1 more stride to cover remaining one step.
Thus, the API returns 6 as the output.

A comma(,) between 2 two flight of steps denotes the landing and each landing takes 2 strides to cover it.
Thus, in above example, 17 steps repeated twice, taking 12 strides for the flight of steps.They are separated by one landing i.e. 2 strides
Therefore, output is 12+2 =14




