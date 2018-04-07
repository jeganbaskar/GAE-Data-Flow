# GAE-Data-Flow

## How to run

To run it direclty in terminal
```
python main.py --input ${INPUT_PATH} --output ${OUTPUT_PATH} --runner ${RUNNER} --project ${PROJECT_ID} --temp_location ${TEMP} --${MODE} --variety ${VARIETY}(optional)
```

INPUT_PATH, path of input file
OUTPUT_PATH, path of output file
RUNNER, the way to run the code, direct or dataflow runner
PROJECT_ID, chen-zeyu-wine-dataflow
TEMP, path of out temp file
MODE, bottles_sold, dollars sold, etc.
VARIETY, to choose the variety of the wines, invalid MODE(purchased_together)


To run it by script, simply run in command line.

Local:
```
chmod +x localrun.sh
./localrun.sh
```

Remote:
```
chmod +x rermoterun.sh
./remoterun.sh
```

The script is written to run all 9 parts.

If you want to change the variety in the script, simply change the variable in the script.

```
VARIETY="yourpreference"
```


