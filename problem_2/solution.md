# Solution to problem 2

Given the files contain values separated by whitespaces, you could use the `wc` command with the `-w` option within a `do if` statement in bash:

	for file in values*; do if test "$(wc -w < "$file")" -lt 100; then echo "${file}"; fi; done

The above would output names of files with fewer than 100 values. In this case the output would be:

	values44
