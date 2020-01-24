Objective:

>Determine which attributes determine what makes a successfull air bnb. 
>Ultimately, we want to know the best place to stay in Hawaii?

  Null hypotheses:
  1. The number of properties rented out by a host has no impact on rating.
    1. host_listings_count
    1. review_scores_rating
    >The neighborhood has no impact on rating/price.
      *neighbourhood_cleansed
      *price
      *review_scores_rating
    >Number of properties has no impact on days available.
      *host_listings_count
      *availability_365
    >Room type has no impact on price/rating.
      *price
      *review_scores_rating
      *room_type
    >Specific keywords in the listing description have no impact of number of overall rating.
      *description
      *review_scores_rating
    >Specific keywords in the tennant reviews have no impact on number of overall rating.
      *comments
      *review_scores_rating
    >The amount of time a host has been renting out their property has no impact on the overall rating.
      *host_since
      *review_scores_rating
    >Time of year has no impact on positive or negative review.
      *date
      *review_scores_rating
    >Proximity to the beach has no impact on number of bookings/overall rating.
      *amenities
      *number_of_reviews
      *review_scores_rating
      *******import additional dataset for this if we have time.
