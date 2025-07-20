<script>
    import Scroller from "../lib/Scroller.svelte";
    import ArticleText from "../lib/ArticleText.svelte";
</script>

<div>
    <Scroller layout="right">
        {#snippet sticky()}
            <img class="asian_edu-img" src="asian_edu.png" alt="Asian Education" />
            <img class="asian_emp-img" src="asian_emp.png" alt="Asian Employment" />
        {/snippet}

        {#snippet scrolly()}
             <ArticleText>
                <strong>
                    Let's take a look into the Asian degree attainment rates and the annual earnings.
                </strong>
            </ArticleText>

            <ArticleText>
                <strong>
                    The graph shows the average of degree attainment rates each year. The highest average attainment rate occured in
                     2023 with approximately 77% which is the highest rate achieved among all other races.
                </strong>
            </ArticleText>

            <ArticleText>
                <strong>
                    The reason behind having the highest average attainment rate may be a result of the Asian culture
                    that places a high value on academic achievments.
                </strong>
            </ArticleText>

            <ArticleText><strong>
                    This graph shows the average of annual median earnings for full-time workers. The highest average of median earnings
                    was in 2022 that had approximately 73,000$ which is also the highest average earnings among all other races.  
                </strong>
            </ArticleText>

            <ArticleText><strong>
                    The high degree attainment rate may be the reason of high annual earnings as Asians in the US tend 
                    to have higher degrees, especially in STEM.
                </strong>
            </ArticleText>
        {/snippet}
    </Scroller>
</div>

<style>
    .asian_edu-img {
       width: 80%;
       margin-top: 15rem;
    }

     .asian_emp-img {
       width: 80%;
       margin-top: 3rem;
    }
</style>
