{
 "cells": [
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "# Data Table Dictionary"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "**INSTRUCTOR TABLE**\n",
    "\n",
    "* InID - Surrogate key acting as the Instructor ID \n",
    "* Name - Full name of instructor\n",
    "\n",
    "**CATALOG TABLE**\n",
    "\n",
    "* CatClass - Surrogate Key for the Catalog ID \n",
    "* CatID - Short for Catalog ID, program name acronym and course level number \n",
    "* Title - Full title name fo course \n",
    "* Description - Course Description\n",
    "* Credits - Numerical credits each course is worth \n",
    "* PID - Surrogate key for Program Name\n",
    "* Prereqs - Course or class standing required to enroll in another course \n",
    "* Coreqs - Course required to be taken simultaneously with another course \n",
    "* Fees - Additional course fee to be collected with registration\n",
    "* Attribute - If a course fulfills a required attribute\n",
    "\n",
    "**PROGRAM TABLE**\n",
    "* PID - Surrogate key for Program Name \n",
    "* PName - Program Name \n",
    "* PCode - Program Code \n",
    "\n",
    "**SECTION TABLE**\n",
    "* SID - Surrogate key acting as the Section ID \n",
    "* CRN - Unique section identifier, although sometimes repeated from semester to semester \n",
    "* Term - Semester and Year \n",
    "* Section - Section Number or Letter of Course \n",
    "* Cap - Capacity of Class\n",
    "* Act - Actual enrollment of class\n",
    "* Rem - Remaining seats left in that class \n",
    "* CatID - Short for Catalog ID, program name acronym and course level number \n",
    "* InID - Surrogate key acting as the Instructor ID \n",
    "\n",
    "\n",
    "**COURSE_MEETING TABLE**\n",
    "* MID - Surrogate key acting as the Course Meetings ID \n",
    "* CRN - Unique section identifier, although sometimes repeated from semester to semester \n",
    "* Term - Semester and Year \n",
    "* Start - Date and start Time of Course Meeting \n",
    "* End - Date and End Time of Course Meeting \n",
    "* Day - Day of week course is meeting on "
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": []
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "Python 3",
   "language": "python",
   "name": "python3"
  },
  "language_info": {
   "codemirror_mode": {
    "name": "ipython",
    "version": 3
   },
   "file_extension": ".py",
   "mimetype": "text/x-python",
   "name": "python",
   "nbconvert_exporter": "python",
   "pygments_lexer": "ipython3",
   "version": "3.6.5"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 2
}
