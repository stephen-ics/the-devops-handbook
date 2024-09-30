# The First Way: The Principles of Flow
- The goal is to increase "flow", or to decrease lead times for deploying code into production
- We achieve this by making work visible, reducing batch sizes and intrervals of work, and by building in quality to prevent defects from being passed to downstream work centers

## Make Our Work Visible
- A big difference between tech and manufacturing vlaue streams is that for tech, the work is invisible
- A great way to help us visualize work flow is to use visual work boards, such as kanban boards or sprint planning boards
- Work originates on the left (often pulled from a backlog) and finishes when it reaches the right side of the board (often labelled "done" or "in production")

## Limit Work In Progress (WIP)
- In manufacturing, daily work is typically dictated by a production schedule that is generated regularly
- In technology our work is usually far more dynamic, this is especially the case in shared services, where teams must satisfy the demands of many different stakeholders
- Interrupting tech workers is easy, because the consequences are invisible to almost everyone, even though the negative impact to productivity may be far greater than in manufacturing
- Studies shows that the time to complete even simple tasks degrades signficiantly when multitasking
- We can limit multitasking when we use kanban board to manage our work, such as by codifying and enforcing WIP (work in progress) limits for each column or work center that puts an upper limit on the number of cards that can be in a column
- For example, we may set a WIP limit of three cards for testing, when there are already three cards in the test lane, no new cards can be added to the lane unles a card is completed or removed from the "in work" column
- Limiting WIP also makes it easier to see problems that prevent the completion of work
- Although it may be tempting to start new work, a far better action would be to find out what is causing the delay and help fix that problem

## Reduce Batch Sizes
- Another key component to creating smooth and fast flow is performing work in small batches
- Large batch sizes result in skyrocketing levels of WIP and high levels of variability in flow, if a problem is found in one body panel, the entire batch has to be scrapped, this results in long lead times and poor qualtiy
- Suppose we have 10 brochures that requires four steps to send and mail: fold the brochure, insert the paper into the envelope, seal the envelope, and stamp the envelope
- The large batch strategy would be to sequentially perform one operation on each of the ten brocuhures while in the small batch strategy all steps required to complete one brochure are completed before starting the next brochure
- If we discover during the envelope sealing operation that we made in error in the first step of folding, we would have to refold and reinsert all ten brochures again
- The equivalent to single piece flow in the technology value stream is realized with continuous deployment (CD), where each change committed to a version control is integrated, tested, and deployed in production

