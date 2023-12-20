Soru 1 Cevap :
select rating, count(*) from film
group by rating <br>
Soru 2 Cevap :
select replacement_cost, count(*) from film
group by replacement_cost
having count(*) > 50 <br>
Soru 3 Cevap :
select store_id, count(*) from customer
group by store_id <br>
Soru 4 Cevap :
select country_id, count(*) from city
group by country_id
order by count(*) desc
limit 1
