<script>
    import Scroller from "../lib/Scroller.svelte";
    import ArticleText from "../lib/ArticleText.svelte";
</script>

<div>
    <Scroller layout="right">
        {#snippet sticky()}
            <img class="black_edu-img" src="black_edu.png" alt="black Education" />
            <img class="black_emp-img" src="black_emp.png" alt="black Employment" />
        {/snippet}

        {#snippet scrolly()}
             <ArticleText>
                <strong>
                    We will now explore the Black degree attainment rates and the annual earnings!
                </strong>
            </ArticleText>

            <ArticleText>
                <strong>
                    First, from the average of degree attainment rates each year. We conclude that the highest average degree attainment 
                    rate was in 2023 with approximately 60% which is actually an achievement as it was the first year the Black 
                    average attainment rate to be above fifties.
                </strong>
            </ArticleText>

            <ArticleText>
                <strong>
                    The limited access to predominantly white institutions may affect the Black access to such institutions
                    consequently, decrease the number of Black who receive degrees.
                </strong>
            </ArticleText>

            <ArticleText><strong>
                   This graph shows the average of annual median earnings for full-time workers. The highest average of median earnings
                    was in 2021 with above 48,500$. This poses a question to determine what led to the 
                    decrease of annual earnings in 2022 although the degree attainment rate increased.
                </strong>
            </ArticleText>

            <ArticleText><strong>
                    The Pay discrimination may play a role in the average of annual median earnings for Black employees
                     as they are offered lower starting salaries and fewer raises/promotions than a White worker.
                    
                </strong>
            </ArticleText>
        {/snippet}
    </Scroller>
</div>

<style>
    .black_edu-img {
       width: 80%;
       margin-top: 15rem;
    }

     .black_emp-img {
          width: 80%;
          margin-top: 3rem;
    }
</style>
