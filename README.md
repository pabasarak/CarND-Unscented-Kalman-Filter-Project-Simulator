
# Unscented Kalman Filter

The normal Kalman filter can handle only linear equations.

Using Extended Kalman filter and Unscented Kalman filter, you can handle none-linear equations.

Extended Kalman filter is the standard solution for nonlinear state equations. However, it not suitable for highly nonlinear states because propagation of uncertainty in EKF will cause significant errors.

As unscented Kalman filter creates sample points around current state estimate and pass them through a nonlinear map. This makes UKF more accurate than EKF for nonlinear state equations.



## Output

RMSE for Simulator Data set 2 is :

0.0784

0.0692

0.5590

0.2490






