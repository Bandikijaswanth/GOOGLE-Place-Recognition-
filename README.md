# GOOGLE-Place-Recognition-
AIM

To implement a threshold-based place recognition system using similarity scores.

PROCEDURE
Initialize similarity score and threshold value
Compare similarity score with threshold
If similarity > threshold, recognize the place
Otherwise, mark as not recognized
Display the result
CODE
# Input values
similarity = 0.94
threshold = 0.9

# Place recognition logic
if similarity > threshold:
    result = "Place Recognized"
else:
    result = "Place Not Recognized"

# Output
print(result)
OUTPUT

Place Recognized

RESULT

The system successfully recognizes the place since the similarity score exceeds the threshold value.
