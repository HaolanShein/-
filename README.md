```c
void calc_pid_xj()
{
  P = error;
  I = I + error;
  D = error - previous_error;
 
  PID_value_xj = (Kp * P) + (Ki * I) + (Kd * D);
 
  previous_error = error;

}
```
