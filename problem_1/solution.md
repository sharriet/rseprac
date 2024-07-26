# Solution to problem 1

1. Change the file extension from bash:

		for file in *.csv; do
    	mv -- "$file" "${file%.csv}.dat"
		done

From [Stack Exchange](https://unix.stackexchange.com/questions/19654/how-do-i-change-the-extension-of-multiple-files)

2. Replicate the changes on the remote:

		git add *.dat
		git rm *.csv
		git commit -m "renaming all .csv files .dat"
		git push origin main
