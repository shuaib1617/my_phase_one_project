{
 "cells": [
  {
   "cell_type": "markdown",
   "id": "3e703797",
   "metadata": {},
   "source": [
    "# BUSINESS UNDERSTANDING"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "5e651747",
   "metadata": {},
   "source": [
    "# INTRODUCTION"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "41b46527",
   "metadata": {},
   "source": [
    "Welcome to the Microsoft Movie Studio Exploratory Data Analysis (EDA) project! In this exploration, we embark on a cinematic journey to unveil the dynamics of the film industry. As Microsoft ventures into movie production, our objective is to decipher critical insights from data analysis, offering guidance to shape the studio's strategic choices. Through this analysis, we will unearth genre preferences, financial correlations, and other essential patterns that will empower Microsoft's foray into the world of film.\n",
    "\n"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "65c73353",
   "metadata": {},
   "source": [
    "# PROBLEM STATEMENT"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "3e37d510",
   "metadata": {},
   "source": [
    "Microsoft is stepping into the movie industry, aiming to establish a successful movie studio. However, with little prior experience in filmmaking, the tech giant faces the challenge of understanding what makes a movie financially successful in today's competitive landscape. To address this, we have undertaken an Exploratory Data Analysis (EDA) to decode the factors that drive box office success. Our mission is to provide actionable insights that will guide Microsoft's movie studio in choosing the right genres, budgets, and creative directions to produce profitable and engaging films.\n",
    "\n"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "78473dcf",
   "metadata": {},
   "source": [
    "# OBJECTIVES"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "c929e4cd",
   "metadata": {},
   "source": [
    "Genre Insights: Explore the distribution of movie genres to identify the most popular and potentially lucrative genres in the current market.\n",
    "\n",
    "Budget and Profit Analysis: Analyze the relationship between production budgets and profits to understand the financial dynamics of successful films.\n",
    "\n",
    "Correlation Examination: Calculate correlations between production budgets, profits, and worldwide gross to uncover patterns and dependencies.\n",
    "\n",
    "Top 10 Genres: Identify the top genres by count, production budget, worldwide gross, and profit to provide actionable recommendations for Microsoft's movie studio."
   ]
  },
  {
   "cell_type": "markdown",
   "id": "2f7a283e",
   "metadata": {},
   "source": [
    "# DATA UNDERSTANDING\n"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "d29e37f3",
   "metadata": {},
   "source": [
    "Data Source\n",
    "\n",
    "The data for this analysis originates from Box Office Mojo and IMDb. Box Office Mojo provides financial information, including production budgets and worldwide gross earnings, while IMDb offers details on movie genres. These combined sources enable a comprehensive exploration of the movie industry.\n",
    "\n",
    "Key Attributes\n",
    "\n",
    "Genres: The dataset contains movie genre information, allowing us to categorize films into different genres for analysis.\n",
    "\n",
    "Production Budget: Production budgets represent movie-making costs and offer insights into investment patterns across genres.\n",
    "\n",
    "Worldwide Gross: Worldwide gross figures indicate a movie's total global box office earnings, reflecting its financial success.\n",
    "\n",
    "Profit: Calculated as the difference between worldwide gross and production budget, profit reveals a movie's profitability.\n",
    "\n",
    "This analysis aims to uncover trends and insights within the movie industry, assisting Microsoft's new movie studio in making informed decisions.\n",
    "\n",
    "\n",
    "\n",
    "\n",
    "\n",
    "\n",
    "\n"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "8bad287a",
   "metadata": {},
   "source": [
    "# DATA DECISION"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "98537e7f",
   "metadata": {},
   "source": [
    "I decided to focus only on productions budgets and a worldwide gross of more than $10million. Also, focused on movies with a rating of five and above"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "d8edc759",
   "metadata": {},
   "source": [
    "# CONCLUSION"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "2faa97be",
   "metadata": {},
   "source": [
    "a) There is a positive correlation between profit and production budget.\n",
    "b) Drama, Action, Comedy, Adventure, and Thriller emerge as the top five genres by count in the dataset, providing valuable insights into audience preferences for Microsoft's movie studio venture.\n",
    "C) Genres like Adventure, Action, Drama, Comedy, and Sci-Fi stand out with the highest production budgets, providing valuable insights for budget allocation in Microsoft's movie production pursuits.\n",
    "d) Genres such as Adventure and Action have exhibited significant worldwide gross earnings, making them potentially lucrative options for Microsoft's new movie studio."
   ]
  },
  {
   "cell_type": "markdown",
   "id": "0e0568a9",
   "metadata": {},
   "source": [
    "# RECOMMENDATIONS"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "0c45df51",
   "metadata": {},
   "source": [
    "a) Genre Focus: Consider investing in genres that have a high count, as they tend to attract a larger audience. Genres like Drama, Action, and Comedy are popular choices.\n",
    "\n",
    "b) Budget Allocation: Allocate your budget wisely. While genres like Adventure and Action may require higher budgets, genres like Drama and Comedy can often achieve a good balance between budget and profit.\n",
    "\n",
    "c) Profitable Genres: Pay attention to genres with high profits, such as Adventure and Action. These genres have a track record of delivering substantial returns on investment.\n",
    "\n",
    "d) Low Budget, High Profit: Explore genres that can generate high profits despite lower production budgets. Genres like Thriller and Crime might offer opportunities for cost-effective filmmaking."
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "49fbe0aa",
   "metadata": {},
   "outputs": [],
   "source": []
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "Python (learn-env)",
   "language": "python",
   "name": "learn-env"
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
   "version": "3.11.4"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 5
}
