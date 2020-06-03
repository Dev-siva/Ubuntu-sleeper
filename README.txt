# Copy the entire folder as zip into docker engine machine
Pre-req's for engine machine are wget and unzip packages 

- CMD # Throws error missing arg when you run the contianer
docker build -t unbuntusleeper .

- CMD -ARg 
docker build -t unbuntusleeper1 .

- ENT # MUST PASS THE ARG value***
docker build -t unbuntusleeper2 .

- ENT -arg
docker build -t unbuntusleeper3 .

- ENT -Arg + CMD
- ENT
docker build -t unbuntusleeper4 .

