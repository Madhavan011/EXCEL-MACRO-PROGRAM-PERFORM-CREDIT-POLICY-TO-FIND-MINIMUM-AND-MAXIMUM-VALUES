# EXCEL-MACRO-PROGRAM-PERFORM-CREDIT-POLICY-TO-FIND-MINIMUM-AND-MAXIMUM-VALUES
Sub AA()

Dim A As Integer

Dim B As Integer

Dim C As Integer

Dim D As Integer

Dim result As Integer 

A = InputBox("Enter number 1")

B = InputBox("Enter number 2")

C = InputBox("Enter number 3")

D = InputBox("Enter number 4")

result = WorksheetFunction.Max(A, B, C, D) 

MsgBox "The maximum number is: " & result

End Sub
