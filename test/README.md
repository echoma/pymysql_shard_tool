* Before run any test, setup the test mysql user with this sql: `mysql -uroot -e "grant all on *.* to test@'localhost' identified by 'test' with grant option"`

* Run all test cases with this command: `make -s`

| test case | work flow | filter | order by | paging | group_method | group_int list |
| ------ | ------ | ------ | ------ | ------ | ------ | ------ |
| test_case_01 | A | N | N | N | modulus | N |
| test_case_02 | A | Y | Y | Y | modulus | N |
| test_case_03 | A | N | N | N | devide | N |
| test_case_04 | B | N | N | N | modulus | Y |
| test_case_05 | C | N | N | N | devide | N |
| test_case_06 | D | Y | Y | Y | devide | Y |
| test_case_07 | C | N | N | N | all | N |
