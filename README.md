Hello, can you create a Python program that can create a shift schedule with day of the week for 20 employees from september 1 to september 30, 2023. The 20 are CHEF1, CHEF2, COZ1, COZ2, COZ3, COZ4, ASG1, ASG2, ASG3, ASG4, AUX1, AUX2, CONF1, AUXPIZ1, PIZ1, PIZ2,  GARD1, GARD2, MASSA1, MASSA2.

Rules:
* ~~Each day has two shifts - Morning shift and Evening Shift.~~
* ~~Each person has to have at least 1 day off on a sunday per month~~
*If possible whoever has the sunday off has monday off as well
*Each person has to have 2 days off per week.
* ASG1, ASG2, ASG3, ASG4 don't have two shifts together on the same day. Their work schedule is separate from the rest of employees.
* CHEF1,  COZ1, COZ2, ASG1, ASG2,  AUX1, CONF1,  PIZ1,   GARD1, MASSA1,  get only morning shifts. Only exception is when they do two shifts on the same day.
*CHEF2,  COZ3, COZ4,  ASG3, ASG4, AUX2, AUXPIZ1,  PIZ2,   GARD2, MASSA2 get only evening shifts. Only exceptions are sundays and when they do two shifts on the same day.
* The same person should only have two shifts together on the same day when there is a day off next day.
* ~~CONF1 and AUXPIZ1 have the same competences.~~
* ~~Sunday Evening Shift is reduced with only 3 people. CHEF1 or CHEF2 plus any two of the following: PIZ1, PIZ2, AUXPIZ1.~~
Unassigned shifts are allowed - the manager will find a way to assign them later.


Equipe de cozinha, 4 auxiliares de serviços gerais (ASG) que fazem a pia.
4 cozinheiros (COZ)
2 auxiliares de cozinha (AUX)
2 Pizzaiolos (PIZ)
1 auxiliar pizzaiolo (AUXPIZ)
2 gard manger (cozinha fria, GARD)
2 masseiros (MASSA)
1 confeiteiro ( CONF)