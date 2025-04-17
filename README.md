public class JobPosting {
    private int id;
    private String companyName;
    private String positionName;
    private String description;
    private String requirements;
    private double salary;
    private String location;
    private boolean isActive;

    // 构造函数
    public JobPosting(int id, String companyName, String positionName, String description, String requirements, double salary, String location, boolean isActive) {
        this.id = id;
        this.companyName = companyName;
        this.positionName = positionName;
        this.description = description;
        this.requirements = requirements;
        this.salary = salary;
        this.location = location;
        this.isActive = isActive;
    }

    // Getter 和 Setter 方法
    public int getId() {
        return id;
    }

    public void setId(int id) {
        this.id = id;
    }

    public String getCompanyName() {
        return companyName;
    }

    public void setCompanyName(String companyName) {
        this.companyName = companyName;
    }

    public String getPositionName() {
        return positionName;
    }

    public void setPositionName(String positionName) {
        this.positionName = positionName;
    }

    public String getDescription() {
        return description;
    }

    public void setDescription(String description) {
        this.description = description;
    }

    public String getRequirements() {
        return requirements;
    }

    public void setRequirements(String requirements) {
        this.requirements = requirements;
    }

    public double getSalary() {
        return salary;
    }

    public void setSalary(double salary) {
        this.salary = salary;
    }

    public String getLocation() {
        return location;
    }

    public void setLocation(String location) {
        this.location = location;
    }

    public boolean isActive() {
        return isActive;
    }

    public void setActive(boolean active) {
        isActive = active;
    }

    @Override
    public String toString() {
        return "JobPosting{" +
                "id=" + id +
                ", companyName='" + companyName + '\'' +
                ", positionName='" + positionName + '\'' +
                ", description='" + description + '\'' +
                ", requirements='" + requirements + '\'' +
                ", salary=" + salary +
                ", location='" + location + '\'' +
                ", isActive=" + isActive +
                '}';
    }
}
