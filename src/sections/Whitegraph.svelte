<script>
    import Scroller from "../lib/Scroller.svelte";
    import ArticleText from "../lib/ArticleText.svelte";
</script>

<div>
    <Scroller layout="right">
        {#snippet sticky()}
            <img class="white_edu-img" src="white_edu.png" alt="white Education" />
            <img class="white_emp-img" src="white_emp.png" alt="white Employment" />
        {/snippet}

        {#snippet scrolly()}
            <ArticleText>
                <strong>
                    Uncovering the White degree attainment rates and the annual earnings....
                </strong>
            </ArticleText>

            <ArticleText>
                <strong>
                   The graph clearly shows the average of degree attainment rates each year. It is apparent that the highest 
                     average attainment rate occured in 2023 with above 68% which is the second highest degree attainment
                     rate among races after Asians.
                </strong>
            </ArticleText>

            <ArticleText>
                <strong>
                    The High-income of White may affect their degree attainment rates as they are more 
                    likely to afford tuition, books, housing, etc
                </strong>
            </ArticleText>

            <ArticleText><strong>
                    This graph shows the average of annual median earnings for full-time workers. The highest average of
                     median earnings was in 2022 with approximately 58,000$ which is also
                     the second highest average of annual median among races after Asians.
                    
                     
                </strong>
            </ArticleText>

            <ArticleText><strong>
                    The overrepresentation of White in high-paying professional and managerial roles may have
                    a strong influence on their annual median earnings.
                </strong>
            </ArticleText>

        {/snippet}
    </Scroller>
</div>

<style>
    .white_edu-img {
         width: 80%;
        margin-top: 15rem;
    }

     .white_emp-img {
         width: 80%;
         margin-top: 3rem;
    }
</style>


