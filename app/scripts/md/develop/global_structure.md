# global structure 變數解釋

enum 

   {

        PWM1_CCR=0, //pwm input capture connect to radio control ch1

        PWM2_CCR, //pwm input capture connect to radio control ch2

        PWM3_CCR,//pwm input capture connect to radio control ch3

        PWM4_CCR,//pwm input capture connect to radio control ch4

        PWM5_CCR,//pwm input capture connect to radio control ch5

        RC_EXP_ROLL,//expectation  of roll angle

        RC_EXP_PITCH,//expectation  of pitch angle

        RC_EXP_YAW,//expectation  of yaw angle

        RC_EXP_THR,//expectation  of throttle value

        TRUE_ROLL,//the roll angle which calculate by AHRS

        TRUE_PITCH,//the roll angle which calculate by AHRS

        TRUE_YAW,//the roll angle which calculate by AHRS

        NO_RC_SIGNAL_MSG,//No radio control signal status

        PID_ROLL,//the value of pid output, this directly means PWM CCR

        PID_PITCH,//the value of pid output, this directly means PWM CCR

        PID_YAW,//the value of pid output, this directly means PWM CCR

        MOTOR1,//Motor 1 CCR(PWM9 )

        MOTOR2,//Motor 2 CCR(PWM10)

        MOTOR3,//Motor 3 CCR(PWM11)

        MOTOR4,//Motor 4 CCR(PWM12)

        GLOABAL_PARAM_COUNT

};