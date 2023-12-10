//:airplane: Credit Rewards Converter :airplane:
//This is the project repo for the JPMC Software Engineering Lite Program, consult the program instructions for more information.


public rewardsValue{
    double getMilesValue(double val){
        try {
            val = Double.parseDouble(input_value);
        } 
        catch (NumberFormatException exception) {
            System.out.println("Could not parse input value as a double, exiting");
            return;
        
    }
    return(val/100);
}
}
