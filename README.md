# performance
To run test plan in Non-GUI mode:
1. Open command prompt
2. Go into JMeter’s bin folder
3. Enter following command: `jmeter -n -t %test_plan_name.jmx% -l %log_file_name.jmx% -Jusers=%number_of_users% -Jrump-up=%rump-up_number% -Jduration=%duration_number%`

Example of the command that was used to create result.csv: `jmeter -n -t C:\Users\Anastasiia_Fedianina\Downloads\perfomance\03.06.2020\challenger_test_plan.jmx -l C:\Users\Anastasiia_Fedianina\Downloads\perfomance\03.06.2020\result.csv -Jusers=3 -Jrump-up=10 -Jduration=300`
