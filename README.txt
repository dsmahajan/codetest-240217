Changes done
1. Formatting
    - Added function inputs & return type at all places (previously it was there for some functions only)
    - Different types of if-else blockd were used. I changed them to single format, just to maintain similarity.
    - Changed variable to snake case, previously some were in camel-case & few were in snake-case (Just to maintain similarity)

2. Structure 
    - Seen somewhere we were writing queries (with, find etc) directly in cotroller, which is not as per the MVC pattern. So created similar function in repository & called that function from Controller. e.g. BookingRepository->getJobData().
    - Also kept relations array as optional param to that function.
    
3. Logic
    - Removed else block from some places where only if was enough, just by adding else staement before start of if.