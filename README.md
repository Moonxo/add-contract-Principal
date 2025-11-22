# add-contract-Principal
  contract Principal is ITeacher {
    function annualSalary() external pure override returns (uint) {
        return 200_000;
      }
