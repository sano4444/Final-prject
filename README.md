#pragma once
#include <vector>
#include <string>
#include <iostream>
#include <algorithm>
#include "CourseInfo.h"
using namespace std;
class Schedule {
private:
    CourseList* courses;
public:
    void displayWeeklySchedule();
    void displayDay(char day);
    void setCourseList(CourseList* list);
    void AddCourse(CourseInfo c);
    vector<CourseInfo> GetCourseList();
};
